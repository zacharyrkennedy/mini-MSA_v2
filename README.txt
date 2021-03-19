miniMSA-Version 2 | By Zachary Kennedy | Last Updated 3/8/2021

This is the python code for collecting and storing data on the miniMSA version 2. It collects data of green house gases using a Winsen ZPHS01B
sensor board. In addition to the sensor board, this code is equiped for use with a ublox-CAM-M8Q GPS to get longitude and latitiude readings.

This code collects data every 7 seconds and stores it in a file with the name and date of when the sensor began collecting data.

The text files stores each data point seperated by commas. This allows for easy data analysis using python or excel.

Data is written to the file in the following order:

Time in MST, Mission Elapsed Time, latitude, longitude, gps heading, pm1.0, pm2.5, pm10, CO2, VOC, Temp, rh, CH2O, CO, O3, NO2


For the user's information, I've included links to both of the data sheets for the winsen and the GPS:

Winsen ZPHS01B - https://www.winsen-sensor.com/d/files/air-quality/zphs01b-english-version1_3.pdf

ublox-CAM-M8Q GPS - https://learn.watterott.com/sensors/cam-m8q/cam-m8.pdf
