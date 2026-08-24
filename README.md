<div align="center">

# Winnie Silva

### .NET Developer | Backend & Full Stack

**C# • ASP.NET Core • .NET Framework • SQL Server • Angular • React • TypeScript**

Building and evolving business systems, backend APIs and financial applications.

<br>

<a href="mailto:winniestefany303@gmail.com">
  <img src="https://img.shields.io/badge/Email-0f172a?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<a href="https://www.linkedin.com/in/winnie-silva" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="https://github.com/winnie-s3" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

</div>

---

## About Me

I'm a **.NET Developer with around two years of professional experience** maintaining and evolving a financial system used in production.

My professional work involves understanding business requirements, investigating production issues, implementing features and financial rules, working with databases and validating changes before release.

My day-to-day stack includes:

**C# • .NET Framework • ASP.NET Web Forms • SQL Server • Entity Framework • LINQ • JavaScript • jQuery • AJAX**

Alongside my professional work, I build projects with the modern .NET ecosystem, focusing on:

* ASP.NET Core Web APIs
* RESTful API design
* authentication and authorization
* external API integrations
* Entity Framework Core
* automated tests
* Angular and React frontends
* software architecture and maintainability

Currently studying **Information Systems at Faculdade Impacta**.

---

## Tech Stack

### Backend

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square\&logo=csharp\&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)

`C#` • `.NET Framework` • `ASP.NET Web Forms` • `ASP.NET Core` • `Web APIs` • `Entity Framework` • `Entity Framework Core` • `LINQ`

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square\&logo=angular\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=nextdotjs\&logoColor=white)

`JavaScript` • `TypeScript` • `HTML` • `CSS` • `jQuery` • `AJAX` • `Angular` • `React` • `Next.js`

### Databases

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square\&logo=microsoftsqlserver\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)

`SQL Server` • `PostgreSQL` • `SQLite` • `SQL` • `Stored Procedures`

### Tools & Engineering Practices

`Git` • `GitHub` • `Swagger / OpenAPI` • `Postman` • `xUnit` • `JWT` • `Dependency Injection` • `SOLID` • `OOP` • `Debugging` • `Troubleshooting`

---

# Featured Project

## 📊 Portfolio Manager

> Full stack investment portfolio application built to explore modern .NET development, API integrations, authentication, authorization and financial domain modeling.

🔗 **Repository:**
https://github.com/winnie-s3/portfolio-manager-api

### Architecture

```text
Angular
   │
   ▼
ASP.NET Core Web API
   │
   ▼
Controllers
   │
   ▼
Services
   │
   ├──────────────► External Market Data API
   │
   ▼
Entity Framework Core
   │
   ▼
SQLite
```

### Highlights

* ASP.NET Core REST API
* Angular frontend
* user registration and login
* password hashing with BCrypt
* JWT authentication using `HttpOnly` cookies
* route protection and authentication guards
* user-level authorization and portfolio data isolation
* portfolio management
* asset management
* investment transaction modeling
* external market price integration
* external provider abstraction with Dependency Injection
* normalized external API responses
* centralized exception handling
* logging
* Entity Framework Core migrations
* Swagger / OpenAPI
* pagination and filtering
* initial automated tests with xUnit
* .NET User Secrets for local secrets

### External Integration

Market data access is isolated behind an internal contract:

```text
Application
     │
     ▼
IMarketDataProvider
     │
     ▼
BrapiMarketDataProvider
     │
     ▼
External API
```

The rest of the application does not need to know the provider URL or its response format.

External responses are mapped into internal models, reducing coupling between the application and the external service.

### Authentication Flow

```text
User Login
    │
    ▼
ASP.NET Core validates credentials
    │
    ▼
JWT is generated
    │
    ▼
HttpOnly Cookie
    │
    ▼
Browser sends cookie automatically
    │
    ▼
Protected API endpoints
```

The JWT signing key is kept outside the repository using **.NET User Secrets**, while the authentication token is stored in an **HttpOnly cookie**, preventing direct access from frontend JavaScript.

### Domain Evolution

The project is evolving from a simple portfolio CRUD into an operation-based financial model:

```text
User
  │
  └── Portfolio
        │
        └── InvestmentTransaction
               │
               └── Asset
```

Investment transactions are intended to represent the financial history of the portfolio and become the basis for derived information such as:

* current position
* average price
* invested amount
* portfolio valuation

### Current Development

* [x] Authentication
* [x] Authorization by user
* [x] Angular frontend
* [x] Portfolio management
* [x] External market data integration
* [x] Centralized error handling
* [x] Initial investment transaction support
* [ ] Transaction history by portfolio
* [ ] Sell position validation
* [ ] Position calculation
* [ ] Average price calculation
* [ ] Expanded automated test coverage
* [ ] Portfolio market valuation

### Stack

**C# • ASP.NET Core • Angular • TypeScript • Entity Framework Core • SQLite • LINQ • JWT • BCrypt • xUnit • Swagger • Git**

---

## What I'm Currently Improving

I'm currently focused on strengthening my knowledge of:

* modern backend development with .NET
* API design and integrations
* authentication and authorization
* automated testing
* financial domain modeling
* software architecture
* frontend integration with Angular
* maintainable and testable code

I prefer learning technologies by applying them to real problems and understanding the trade-offs behind each technical decision.

---

<div align="center">

### Let's connect

I'm always interested in exchanging ideas about **.NET, backend development, APIs and software engineering**.

<br>

<a href="https://www.linkedin.com/in/winnie-silva">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

</div>
