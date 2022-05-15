# UFOs Sighting Tracker Website

## Overview of Project
Current project was created in order to accesibly display information on known UFO sightings across the United States. The idea for the project was to create a dynamic webpage that would be responsive to user input when filtering the available UFO sighting information by either date, city, state, country, or shape of the sighted object, so that people could conveniently locate the sighting of interest or investigate UFO sightings in a particular area or timeframe.

## Results
The dynamic webpage has the following overview design:
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/168452363-47951180-3d71-438c-8f59-906aadf82e00.png" />
</p>

### How to utilize the search parameters
It is pretty easy for the end user to navigate the website by entering a number of desired filters (see picture below).
![Screenshot_2](https://user-images.githubusercontent.com/99566803/168452396-767e5f64-9598-41b5-9985-fdb54cabbd68.png)

Generally, all filters act in a similar manner:

* If a user wants to navigate the UFO sightings by **date**, they only need to enter the desired date in the "Enter Date" field, in a DD/MM/YYYY format.
* If a user wants to navigate the UFO sightings by a particular **city**, they simply need to enter the desired city name in the "Enter a City" field.
* Similarly, if a user wants to see UFO sightings in a particular **state**, they only need to enter the desired state code (e.g., "ca" for California) in the "Enter a State" field.
* If a user wants to restrict the search by **country**, they simply need to put the country code (e.g., "us" for USA) in the "Enter a Country" field.
* Finally, if the user wants to filter their UFO sighting results by the UFO **shape**, they only need to enter the desired shape (e.g., "triangle" or "square") in the "Enter a Shape" field.

There are no restrictions as to the amount of filters a user can apply at a time. As such, users can filter their UFO sightings by a single filter (e.g., date), as well as any two or more filters (up to 5 filters total).

## Summary

### Drawback
One particular drawback of the current webpage is that it displays all available UFO sighting by default, thereby increasing the trafic and load that the end user will experience of their end while loading the webpage (which, in a case where users are of a limited internet access subscription plan, might be a big problem).

### Recommendations
One recommendation that I have for user accesibility of the website is to provide each filtered space with a kind of a drop-down menu with all available search options (as, for example, the users might not know all the available city names, or states).

Another recommendation would be to shred down the UFO sighting table by default to a scroll list (with 10 to 15 entries showing at a time), therefore shrinking the webpage vertically (as, otherwise, the users might have to scroll down for a substantially long time to locate a search of interest).
