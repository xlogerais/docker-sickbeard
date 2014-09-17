
This repository contains material to build a docker container for the sickbeard application.

Build
=====

'''docker build --tag sickbeard:latest .'''

Run
===

'''docker run --name sickbeard --publish 8081:8081 --detach sickbeard'''

Then navigate to http://localhost:8081/
