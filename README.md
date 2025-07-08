


blogify-qpp – A Full-Stack MERN Blog Application

blogify-app is a full-featured blogging platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, manage, and explore blog content with a clean interface, secure authentication, and admin-level controls.

# Project Structure

- client/ – React frontend for user interaction and UI rendering  
- server/ – Node.js backend with Express for API routing and business logic



##  Features

###Home Page
- Displays a list of recent blog posts
- Navigation for login, registration, and post creation
- Search functionality to filter posts by keywords

### Authentication
- Secure user registration and login using JWT
- Google OAuth integration for seamless sign-in
- Role-based access (admin vs. regular user)

###  Blog Management
- Authenticated users can create, update, and delete their own posts
- Posts include title, content, image, and optional tags or categories
- Rich text editor for writing and formatting content

### Admin Dashboard
- Accessible only to admin users
- Manage users, posts, and comments
- Perform actions like edit, delete, or block users/posts

### Search & Filter
- Keyword-based search to find specific posts
- Optional filtering by category, author, or date

### Post Details
- View full content of a blog post
- Includes metadata like author, date, and estimated read time
- Optional features: likes, comments, and share options



## Tech Stack

- Frontend: React.js, Axios, Tailwind CSS (or Bootstrap)  
- Backend:Node.js, Express.js  
- Database: MongoDB (with Mongoose)  
- Authentication: JWT, Google OAuth  
- Deployment:Render, Vercel, MongoDB Atlas
