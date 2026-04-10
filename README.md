# Spring Boot CRUD API.

A simple and clean RESTful CRUD API built using Spring Boot, Spring Data JPA, and MySQL.

## 🚀 Features
- Create Employee
- Read All Employees
- Read Employee by ID
- Update Employee
- Delete Employee
- Layered Architecture (Controller → Service → Repository → Entity)

## 🛠 Tech Stack
- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

## 📁 Project Structure
src
 └─ main
    ├─ java
    │   └─ com.yash.employee
    │        ├─ Employee.java
    │        ├─ EmployeeRepository.java
    │        ├─ EmployeeService.java
    │        ├─ EmployeeController.java
    │        └─ SpringbootCrudApiApplication.java
    └─ resources
         └─ application.properties

## 📡 API Endpoints
GET     /api/employees           → Get all employees
GET     /api/employees/{id}      → Get employee by ID
POST    /api/employees           → Create employee
PUT     /api/employees/{id}      → Update employee
DELETE  /api/employees/{id}      → Delete employee

## 🛠 How to Run
1. Update DB config in `application.properties`
2. Create MySQL database
3. Run using:
   mvn spring-boot:run
   OR run the main application class from your IDE.

## 📌 Author
**Yash Advani**  
Java Backend Developer  
GitHub: https://github.com/yash976
