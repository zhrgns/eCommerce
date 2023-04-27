# e-Commerce Spring Boot Application

---
## General Info:

* This project consist of user module for an e-commerce service.
* The API expose an endpoint and the endpoint accepts user's information to make CRUD operations on database.

```
GET /v1/user - retrieves all users
GET /v1/user/{email} - retrieves a user
POST /v1/user - creates a new user
PUT /v1/user/{email} - updates existing user
PATCH /v1/user/{email}/deactivation - deactivates user account
PATCH /v1/user/{email}/activation - activates user account
DELETE /v1/user/{email} - deletes user account
```

## Unit Test

* Includes JUnit tests, and test coverage is 100%.

## Technology

---
- Java 17
- Spring Boot 3.0
- H2 In Memory Database
- Spring Data JPA
- Lombok
- Restful API
- JUnit 5.9, Mockito
- Maven
- Docker
- IntelliJ IDEA

## Prerequisites

----
- Maven or Docker

## Docker Run

----
This application can be built and run using Docker.

```sh
$ cd ecommerce
$ docker build -t ecommerce/demoapp:01 .
$ docker run -p 9090:8080 ecommerce/demoapp:01
```

## Maven Run

---
To build and run the app with `Maven`:

```sh
$ cd ecommerce
$ mvn clean install
$ mvn spring-boot:run
```

---
