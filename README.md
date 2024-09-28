# ZCare - Graduation Project

ZCare is a healthcare management platform developed for managing patients, healthcare providers, appointments, and medical records. This backend system is built with Java, designed for secure, efficient, and scalable healthcare solutions.

## Features
- **Authentication & Authorization**: Secure access using JWT for token-based authentication.
- **Patient Management**: Create, update, and manage patient profiles and medical histories.
- **Appointment Scheduling**: Book, reschedule, and cancel appointments.
- **Medical Records**: Secure handling of patient medical records.
- **Healthcare Providers**: Manage healthcare professional profiles and services.
- **Notifications**: System for important reminders and alerts.
- **Payment Integration**: Supports payment gateways for billing services.
- **RESTful API**: Structured endpoints for client-side interactions.

## Tech Stack
- **Backend**: Java (Servlets, JSP), JPA (Hibernate)
- **Database**: MySQL
- **Security**: JWT (JSON Web Tokens)
- **Deployment**: Apache Tomcat

## Prerequisites
- Java 8+
- Apache Tomcat 9+
- MySQL 5.7+
- Maven 3+

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/zcare-backend.git
   
### 1. Configure the Database:
   - Create a MySQL database.
   - Update the `persistence.xml` file with your MySQL database connection settings (e.g., database URL, username, and password).

### 2. Build the Project:
   mvn clean install
   

### 3. Deploy to Apache Tomcat:
- Copy the generated WAR file from the `target/` directory to the `webapps/` folder of your Tomcat installation.
- Start Tomcat, then access the application at:  
  [http://localhost:8080/zcare](http://localhost:8080/zcare).



## Contribution Guidelines
We welcome contributions! To get started:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix.
3. **Submit a pull request** for review.
