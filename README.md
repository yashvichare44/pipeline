<img width="1470" alt="Screenshot 2025-03-02 at 4 41 14 AM" src="https://github.com/user-attachments/assets/7c8ceb66-3a31-48a6-9ec4-9fa003eea232" />
<img width="1470" alt="Screenshot 2025-03-02 at 4 45 10 AM" src="https://github.com/user-attachments/assets/2f514ad8-7984-4399-8134-ee4e51108876" />
<img width="1470" alt="Screenshot 2025-03-02 at 4 41 07 AM" src="https://github.com/user-attachments/assets/46928154-b60a-4112-b57e-c0bb563d732c" />
<img width="1470" alt="Screenshot 2025-03-02 at 4 40 52 AM" src="https://github.com/user-attachments/assets/4b833e70-14c8-4ad7-8c45-7ed08ad9475b" />
<img width="1470" alt="Screenshot 2025-03-02 at 4 40 02 AM" src="https://github.com/user-attachments/assets/c53e18fa-52b0-4053-85d4-102c79d919e1" />

# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊
