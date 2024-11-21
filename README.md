# Library-Management-using-Cpp-and-MySQL
This project is a role-based library management system developed in C++ with MySQL as the database backend. It provides a simple and efficient solution to manage library operations, including adding books, registering students, and borrowing books. The system is divided into two main roles: Admin and User, each with distinct functionalities.

Features
Admin Module:

Add new books to the library.
Register students in the system.
View the list of available books.
User Module:

Borrow books by entering their student ID and book name.
Check book availability before borrowing.
Automated reduction in book quantity after borrowing.
Database Integration:

Persistent data storage using MySQL.
SQL queries for adding, updating, and retrieving records.
Error Handling:

Handles invalid inputs (e.g., unregistered students, unavailable books).
Displays appropriate error messages for database-related issues.
Technologies Used
Programming Language: C++
Database: MySQL
Libraries:
<mysql.h>: MySQL C API for database interaction.
<windows.h>: Windows-specific operations (e.g., Sleep).
<sstream>: String stream for data formatting.
How It Works
The admin logs in to manage the library (add books, register students).
Users can check available books and borrow them using their student ID.
The system updates the book inventory dynamically.
All operations are backed by a MySQL database, ensuring persistent and consistent data management.
How to Run
Set up MySQL database:

Create a database named mydb.
Create two tables:
lib for storing books (columns: Name and Quantity).
student for storing registered student IDs (column: Id).
Update the connection details (HOST, USER, PW, DB) in the code.
Compile and run the program:

Use a C++ compiler that supports MySQL libraries (e.g., GCC with MinGW or Visual Studio).
Ensure libmysql.dll is available in your environment.
Potential Enhancements
Add a graphical user interface (GUI) for better user interaction.
Implement book return functionality.
Enable logging for admin and user activities.
Support additional roles like Librarian.
Feel free to fork, modify, and use this project to suit your requirements! Contributions are welcome! 🎉
