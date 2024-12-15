# Event Tracker Application

This is an event tracking application built using a Python Tkinter library to create a graphical user interface (GUI). This application allows users to create, manage, and organize events with sorting, filtering, and prioritizing features. 

## Features
- Event Creation and Management: Users can easily book an event by the time and date availability. This project is flexible to adjust schedule for certain events of all forms.  
- Sorting and Prioritizing Events: This application offers sorting features that allows users to organize events base on its date or priority. This allows users to have an organized schedule and prioritize their most to least important event. 
- Event Filtering by Date Range: Users can easily filter events they booked at a specific date range. This enables users to view and manage events within a particular timeframe, making it easier to track upcoming events.

## Requirements for the application to function
- Python 3.x
- Python Tkinter GUI library
- customtkinter library for the custom UI components
- Heap Operation (heapq) to handle prioritized events

## How to run the application 
#### Install the necessary Python libraries 
- install pip customtkinter
#### Download the code files. 
#### Run the Python script 
- python main.py

## Usage 
- Create Event: Enter the event name, date, priority, and time (if it is not an all-day event), then click the "Add Event" button.
- Show Events: Display events sorted by either their priority or date.
- Remove Low Priority Events: Click to remove events with 'low' priority.
- Filter Events by Date: Enter a date range and click "Show Events in Date Range" to filter events. 
