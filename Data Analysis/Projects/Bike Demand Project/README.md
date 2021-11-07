
WELCOME!

The aim of this project is to reveal the current patterns in the data by showing the historical data of London bike shares with visualization tools.

This will allow us to X-ray the data as part of the EDA process before setting up a machine learning model.



#Determines

Features
timestamp - timestamp field for grouping the data
cnt - the count of a new bike shares
t1 - real temperature in C
t2 - temperature in C “feels like”
hum - humidity in percentage
wind_speed - wind speed in km/h
weather_code - category of the weather
is_holiday - boolean field - 1 holiday / 0 non holiday
is_weekend - boolean field - 1 if the day is weekend
season - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.
"weather_code" category description:

1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity
2 = scattered clouds / few clouds
3 = Broken clouds
4 = Cloudy
7 = Rain/ light Rain shower/ Light rain
10 = rain with thunderstorm
26 = snowfall
94 = Freezing Fog
Initially, the task of discovering data will be waiting for you as always. Recognize features, detect missing values, outliers etc. Review the data from various angles in different time breakdowns. For example, visualize the distribution of bike shares by day of the week. With this graph, you will be able to easily observe and make inferences how people's behavior changes daily. Likewise, you can make hourly, monthly, seasonally etc. analyzes. In addition, you can analyze correlation of variables with a heatmap.