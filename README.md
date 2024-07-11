# Metro_Bar_and_Kitchen
Project Overview
This project aims to design and optimize an online restaurant ordering system for The Metro Bar and Kitchen, located on the University of Bedfordshire's Luton campus. The system is built using Laravel 9.0 and MySQL to provide a robust and efficient solution.

Prerequisites
Before you start, ensure you have the following installed on your machine:

PHP (version 7.4 or higher)
Composer
MySQL
phpMyAdmin (optional but recommended for database management)
Getting Started
Step 1: Download the Project
Download the Code: Obtain the entire codebase for the project.
Unzip the Folder: Extract the downloaded zip file to a folder on your machine.
Step 2: Set Up the Environment
Open Command Prompt: Navigate to the unzipped project folder using the command prompt or terminal.
Install Composer Dependencies: Run the following command to install all necessary dependencies:
sh
Copy code
composer update
Step 3: Set Up the Database
Create a Database: Create a new database in MySQL. You can do this via phpMyAdmin or using the MySQL command line:

sql
CREATE DATABASE metro_bar_kitchen;
Import the Database: Upload the provided database file to your MySQL server. This can be done via phpMyAdmin by selecting the newly created database and using the 'Import' function.

Configure the .env File:

Locate the .env file in the project folder.
Update the database settings to match your MySQL setup. For example:
env

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=metro_bar_kitchen
DB_USERNAME=your_username
DB_PASSWORD=your_password
Step 4: Run the Application
Serve the Application: Start the Laravel development server using the following command:

php artisan serve
Access the Application: Open your web browser and navigate to:

http://localhost:8000
Additional Notes
Database Connection: Ensure that your MySQL server is running and that the credentials in the .env file are correct.
Composer: If you do not have Composer installed, you can download it from getcomposer.org.
PHP Version: Ensure that you are running a compatible version of PHP (7.4 or higher). You can check your PHP version by running:
sh
Copy code
php -v
By following these steps, you should be able to set up and run the online restaurant ordering system for The Metro Bar and Kitchen. If you encounter any issues, make sure to double-check your environment settings and dependencies.
