# 🧪 Oza Laboratory Management System 🧬

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![PERN Stack](https://img.shields.io/badge/stack-PERN-orange.svg)

## 📋 Overview

The Oza Laboratory Management System is a comprehensive web application built on the PERN (PostgreSQL, Express, React, Node.js) stack. This system streamlines laboratory operations by managing patients, tests, reports, and disease tracking in a secure and efficient manner.

## ✨ Features

- **🧑‍⚕️ Patient Management**
  - Register new patients with comprehensive profiles
  - Track patient history and test results
  - Manage patient appointments and follow-ups

- **📅 Appointment Scheduling**
  - Book time slots for laboratory tests and consultations
  - Automated confirmation and reminder system
  - Calendar view for availability management
  - Rescheduling and cancellation capabilities

- **🔬 Laboratory Test Management**
  - Define and customize test parameters
  - Organize tests by categories and departments
  - Set reference ranges and critical values

- **📊 Report Generation**
  - Create professional, customizable reports
  - Export reports in multiple formats (PDF, CSV, Excel)
  - Automated result analysis and flagging of abnormal values

- **🦠 Disease Tracking**
  - Record and monitor new disease outbreaks
  - Track disease patterns and statistics
  - Generate epidemiological reports

- **📈 Analytics Dashboard**
  - Real-time laboratory performance metrics
  - Test volume and result statistics
  - Revenue and operational insights

- **🔐 User Authentication & Authorization**
  - Role-based access control (Admin, Lab Technician, Doctor, Receptionist)
  - Secure login with JWT authentication
  - Audit trails for all system activities

## 🛠️ Technology Stack

- **Frontend**
  - React.js with TypeScript
  - Redux for state management
  - Material UI / Tailwind CSS for responsive design
  - Chart.js for data visualization

- **Backend**
  - Node.js with Express framework
  - PostgreSQL database
  - Prisma ORM for database operations
  - JWT for authentication

- **API Documentation**
  - Swagger UI for interactive API documentation
  - OpenAPI specification

- **DevOps**
  - Docker for containerization
  - GitHub Actions for CI/CD
  - Jest and React Testing Library for testing

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/GarudaR007X/Oza_Laboratory_webapp.git
cd Oza_Laboratory_webapp

# Install dependencies for frontend
cd client
npm install

# Install dependencies for backend
cd ../server
npm install

# Set up environment variables
cp .env.example .env
# Edit .env file with your database credentials and other configurations

# Set up the database with Prisma
npx prisma migrate dev

# Run the application in development mode
npm run dev
```

## 🚀 Deployment

```bash
# Build the client
cd client
npm run build

# Start the production server
cd ../server
npm run start
```

## 📝 API Documentation

API documentation is available at `/api-docs` when the server is running. This interactive documentation is generated using Swagger UI and provides detailed information about all available endpoints.

## 🧪 Testing

```bash
# Run backend tests
cd server
npm run test

# Run frontend tests
cd client
npm run test
```


## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

Project Link: [https://github.com/GarudaR007X/Oza_Laboratory_webapp](https://github.com/GarudaR007X/Oza_Laboratory_webapp)

---

⭐️ From [GarudaR007X](https://github.com/GarudaR007X)
