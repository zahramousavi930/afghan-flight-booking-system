# Afghan-flight-booking-system

A Django application for booking flights that is coded in Python, HTML, CSS, and Javascript. The final project for the CS50 course Web Programming with Python and Javascript is this one.

![Responsice Mockup](flight/static/img/home.PNG)

# Features

1. Users can create their user account.
2. Users can book both one-way as well as round-trip tickets.
3. Webpages are mobile responsive.
4. Users can cancel their booked tickets.
5. Users can view their previously booked tickets (Both confirmed and cancelled tickets).
6. Tickets are downloadable as pdf document.
7. As-you-type Search

# Files & Directories
1. capstone - project directory.
2. utils.py - Contains all Django helper functions used in views.py.
3. urls.py - This file handles all the URLs of the project.
4. flight - main application directory.
5. static - contains all static content.
6. css - Contains all css files for styling the webpages.
7. js - Contains all javascript files used in the application.
8. img - Contains all image files used in the application.
9. templates/flight Contains all application templates.
10. book.html - Template for showing selected flight and reading Travellers data.
11. bookings.html - Template for showing bookings done by a user.
12. index.html - Home page template.
13. layout.html - Base template for all pages except login & register page.
14. layout2.html - Base template for login & register page.
15. login.html - Login user page.
16. payment_process.html - Page after completion of payment.
17. payment.html - Payment page.
18. register.html - Register user page.
19. search.html - Flight search result page.
20. ticket.html - Template for printing ticket(pdf).
21. admin.py - Contains some models for access to the Django administrator.
22. models.py - All models used in the application are created here.
23. urls.py - This file handles all the URLs of the web application.
24. views.py - This file contains all the application views.
25. constant.py - This file contains the fee amount which is charged to the user for booking flight tickets.
26. requirements.txt - This file contains all contains all the python packages that needs to be installed to run this web application.
27. manage.py - This file is used basically as a command-line utility and for deploying, debugging, or running our web application.

# Justification
1. Mobile responsive webpages.
2. More complex models.
3. More interatactive because webpages use ajax functionality (eg., fetch) written in javascript.
4. Converts html template to downloadable pdf.

# Installation
1. Install project dependencies by running py -m pip install -r requirements.txt.
2. Run the commands py manage.py makemigrations and py manage.py migrate in the project directory to make and apply migrations.
3. Create superuser with py manage.py createsuperuser. This step is optional.
4. Run the command py manage.py runserver to run the web server.
5. Open web browser and goto 127.0.0.1:8000 url to start using the web application.

yo can see my website: https://afghan-flight-booking-system.herokuapp.com/
