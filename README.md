# World_Weather_Analysis

### Project Overview

PlanMyTrip is a top travel technology company specialized in internet related services in the hotel and lodging industry.
This project will enhance the user interface and functionalities of the PlanMyTrip app with the following steps:

retrieve weather data including the weather description for over 500 cities across the world,
create a customer travel destinations map,
create a travel itinerary map.

This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

## Weather Database
This folder uses Open Weather Map API to pull weather information on over 720 different cities around the world. That information consists of:

Maximum Temperature
Cloudiness
Wind Speed
Humidity
Current Weather Description
These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

## Vacation Search
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. 


## Vacation Itinerary
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary.

### Resources
Data Source: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

### Results

# Retrieve weather data
The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).
The Python's citipy module is then called to identify the nearest city for each coordinate combination.
The weather data is retrieved for all identified cities through a request to the OpenWeatherMap API.

# Create a customer travel destinations map
With Jupyter's gmaps plugin, user's weather preference inputs and requests to the Google Maps and Places API, the app generates a customer travel destinations map.

# Create a travel itinerary map
Using Google Maps Directions API the app generates a travel route between 4 cities selected by the user.


