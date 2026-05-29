# Java-Servlet-Login-Page
Developed a login authentication system using Java Servlets, JSP, PostgreSQL, and JDBC. Implemented user verification by connecting the frontend login page with a PostgreSQL database through Servlets.

# Java Servlet Login System

A beginner-level login authentication system developed using:

* Java Servlets
* JSP
* PostgreSQL
* JDBC
* Apache Tomcat
* HTML/CSS

## Features

* User Login Authentication
* Database Verification
* JSP Success and Failure Pages
* PostgreSQL Integration
* Servlet-Based Backend Processing

## Technologies Used

* Java
* Jakarta Servlet
* PostgreSQL
* JDBC Driver
* Apache Tomcat
* Eclipse IDE

## Database

Table: `users`

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(50)
);
```

## Sample User

Username: admin
Password: 1234

## How to Run

1. Install Apache Tomcat
2. Add PostgreSQL JDBC Driver
3. Create PostgreSQL database
4. Run project on server
5. Open:

```text
http://localhost:8080/LoginProject/login.html
```

## Learning Outcome

This project helped me understand:

* Servlets
* JDBC connectivity
* SQL query execution
* JSP pages
* Backend login authentication
* Database integration with Java

