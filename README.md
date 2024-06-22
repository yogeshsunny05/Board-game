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

## Some screenshots

![Screenshot 2024-06-22 140919](https://github.com/yogeshsunny05/Board-game/assets/139520226/9b5e9c5d-cd04-4486-9547-cdb9681eb7c8)

![Screenshot 2024-06-22 140758](https://github.com/yogeshsunny05/Board-game/assets/139520226/0bc96494-5ded-40eb-8ee2-6c99ace8c659)

![Screenshot 2024-06-22 141029](https://github.com/yogeshsunny05/Board-game/assets/139520226/5bbcc397-97fa-4c4b-8a1a-e4ac5c5cdd18)

![Screenshot 2024-06-22 141450](https://github.com/yogeshsunny05/Board-game/assets/139520226/22225e48-530a-4b93-b302-1fffe4ccaa10)

![Screenshot 2024-06-22 140818](https://github.com/yogeshsunny05/Board-game/assets/139520226/649e2c19-0ca4-4162-bdef-2b6489f43a0d)

![Screenshot 2024-06-22 140958](https://github.com/yogeshsunny05/Board-game/assets/139520226/eb89ca58-b1ca-4354-ae0f-7731eecd7817)
