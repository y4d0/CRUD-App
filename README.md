# CRUD Application for User Management

## Project Overview
This CRUD (Create, Read, Update, Delete) application is a simple user management system that allows users to perform basic operations on user data. The app is built using Node.js, Express.js, and MongoDB, and is designed as part of a 7th-semester project for B.Tech CSE.

## Features
- **Create**: Add new users with details like name, email, gender, and status.
- **Read**: View the list of users.
- **Update**: Modify user details.
- **Delete**: Remove users from the system.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, EJS templating
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: Custom CSS and Bootstrap (for responsive design)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/y4d0/CRUD-App.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up MongoDB:
   - Create a MongoDB database (or use MongoDB Atlas).
   - Configure the database connection in the `server.js` file.

4. Run the application:
    ```bash
    npm start
    ```

5. Open your browser and go to `http://localhost:3000` to access the application.

## Folder Structure
/CRUD-App
├── /node_modules      # Project dependencies
├── /public            # Static files (CSS, JavaScript)
├── /server            # Backend (Node.js, Express)
│   ├── /models        # MongoDB Models
│   ├── /routes        # API Routes
│   └── server.js      # Main entry point
├── /views             # EJS templates
├── .gitignore         # Git ignore file
└── package.json       # Project metadata and dependencies
