# Analyzing-wildfire-activities-in-Australia_2

Practice Assignment: Part 2 - Creating Dashboards

In this lab you will practice creating dashboards using flight summary data.

Skills Network Labs (SN Labs) is a virtual lab environment used in this course. Upon clicking the "Launch App" button below, your Username and Email will be passed to SN Labs and will be used in strict accordance with IBM Skills Network Privacy policy, such as for communicating important information to enhance your learning experience. 

In case you need to download the lab instructions click HERE to open in a new tab.

# About Skills Network Cloud IDE

This Skills Network Labs Cloud IDE (Integrated Development Environment) provides a hands-on environment in your web browser for completing course and project related labs. It utilizes Theia, an open-source IDE platform, that can be run on desktop or on the cloud.
So far in the course you have been using Jupyter notebooks to run your python code. This IDE provides an alternative for editing and running your Python code. In this lab you will be using this alternative Python runtime to create and launch your Dash applications.

Important Notice about this lab environment
Please be aware that sessions for this lab environment are not persisted. When you launch the Cloud IDE, you are presented with a ‘dedicated computer on the cloud’ exclusively for you. This is available to you as long as you are actively working on the labs.

Once you close your session or it is timed out due to inactivity, you are logged off, and this ᴥd computer on the cloud嬥ted along with any files you may have created, dowloaded or installed. The next time you launch this lab, a new environment is created for you.

If you finish only part of the lab and return later, you may have to start from the beginning. So, it is a good idea to plan to your time accordingly and finish your labs in a single session.

# Components of Dashboard and Expected layout

Components of the Dashboard

Select Region

Select Year

Divison to display

Pie Chart to display Monthly Average Estimated Fire Area for the selected Regions in the selected Year
Bar Chart to display Monthly Average Count of Pixels for Presumed Vegetation Fires for the selected Regions in the selected Year

# Requirements to create the expected result

A dropdown menu: For choosing year
A radioitem for choosing the Region
The layout will be designed as follows:
An outer division with two inner divisions (as shown in the expected layout)
One of the inner divisions will have information about the radioitem and dropdown (which are the input) and the other one is for adding graphs(the 2 output graphs).
Callback function to compute data, create graph and return to the layout.

# To do:

Import required libraries and read the dataset
Create an application layout
Add title to the dashboard using HTML H1 component
Add a radioitem using dcc.RaioItems and dropdown using dcc.dropdown
Add the pie chart and bar chart core graph components.
Run the app
