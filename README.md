# Car Rental Management System
A comprehensive Python-based CLI application designed to manage staff, customers, and vehicle fleets for a car rental service. This project was developed as part of a Programming with Python module during a Diploma in Information and Communications Technology (with a specialism in Software Engineering).

## 📌 Project Overview
The system provides a centralized platform for three distinct user roles—Managers, Customer Service Staff, and Car Service Staff—to perform specific administrative and operational tasks. The application uses Object-Oriented Programming (OOP) principles to handle customer data and manages data persistence through text file exports.

## 🛠️ Features
### 1. Manager Module
Staff Management: Register new staff, update details, and view the current staff list.

Operational Oversight: Update car renting rates based on seating capacity (4, 7, or 9 seaters).

Reporting: Generate monthly revenue reports based on completed rental transactions.

Data Export: Export the full staff list to staff_list.txt.

### 2. Customer Service Module
Customer Records: Register new customers, update profiles, and view or delete customer records.

Rental Processing: Search for available cars by seating capacity and process rental transactions including date validation and payment calculation.

Billing & Tracking: Generate individual customer bills and view all transactions for a specific date.

Data Export: Export customer lists to customers.txt.

### 3. Car Service Module
Fleet Management: Register new vehicles including details like engine number, manufacturer, and seating capacity.

Maintenance Tracking: Update insurance policy numbers, road tax expiry dates, and rental availability status (e.g., "available", "under service", or "disposed").

Data Export: Export the vehicle inventory to cars_list.txt.

## 💻 Tech Stack
Language: Python 3.x

Libraries: datetime (for handling rental durations and date validation)

Data Storage: Dictionary-based in-memory storage with text file exports

## 🚀 How to Run the Project
Prerequisites: Ensure you have Python 3.x installed on your machine.

### Clone the Repository:

Bash
git clone https://github.com/wongzoey/car-rental-system.git
Execute the Script:
Navigate to the project folder and run:

Bash
python "Main file (1).py"

### Login Credentials:

The system uses a role-based authentication system. Default accounts include:

Manager: Username: alex | Password: 12345

Customer Service: Username: bob | Password: 123

Car Service: Username: tom | Password: password123
