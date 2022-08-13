# Leaflet-challenge
![cover](Images/cover.png)
Visualizing Data with Leaflet  for Earthquake Visualization
## Level 1: Earthquakes Basic Visualization
I used USGS GeoJSON Feed to get the data and visualized all Earthquakes from the Past 7 Days.

* The map is created using Leaflet, which plots all earthquakes from the data set based on their longitude and latitude.
* Data markers are also used to reflect the earthquake's magnitude in their size and color. Earthquakes with higher magnitudes should appear more significant in the color spectrum, starting from green to red, which means when magnitude increases, the color goes from green to red.
Popups are included to provide additional information about the earthquake when a marker is clicked
* legend added to give the context of the map data.
* The map looks as:

![level1](Images/level1.png)


## Level 2: Earthquakes Advanced Visualization
I added a second data(layer) set on the map to illustrate the relationship between tectonic plates and seismic activity in this task. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.

In this task:

I plotted a second data set on the map.

Added a number of base maps to choose from and separated our two different data sets into overlays that can be turned on and off independently.

Add layer controls to the map.
![level2](Images/Level2.png)