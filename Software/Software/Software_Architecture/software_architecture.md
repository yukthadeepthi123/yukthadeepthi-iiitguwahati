This file describes the software architecture of the Smart Waste Bin Monitoring System.

Software Architecture Overview:
- Sensor data is collected periodically from waste bins
- ESP32 processes raw sensor data and calculates fill percentage
- Data is transmitted to the cloud using MQTT protocol
- Cloud services handle data storage, alerts, and analytics
- Dashboard visualizes bin status and supports route optimization

