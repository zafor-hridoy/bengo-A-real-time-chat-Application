# 💬 Bengo - Real-time Chat Application

A modern, full-stack real-time chat application built with the MERN stack. Bengo provides a seamless messaging experience with features like instant message delivery, online status updates, theme customization, and secure authentication.

## 📑 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Environment Variables](#-environment-variables)
- [Running the Application](#-running-the-application)
- [Project Structure](#-project-structure)

## ✨ Features

- **Real-time Messaging**: Instant message delivery and updates using Socket.io.
- **User Authentication**: Secure signup and login with JWT and bcrypt.
- **Online Status**: Real-time online/offline user status indicators.
- **Image Sharing**: seamless image upload and sharing powered by Cloudinary.
- **Theme Customization**: Choose from 30+ themes (DaisyUI) to personalize your chat interface.
- **Responsive Design**: Fully responsive UI that works great on desktop and mobile.
- **Modern UI/UX**: Clean interface with skeletons, toast notifications, and smooth animations.
- **Profile Management**: Easy profile updates and avatar management.

## 🛠 Tech Stack

**Frontend:**
- **React 19**: Modern UI library for building interactive interfaces.
- **Vite**: Next-generation frontend tooling.
- **Tailwind CSS & DaisyUI**: Utility-first CSS framework for rapid UI development.
- **Zustand**: Small, fast and scalable bearbones state-management solution.
- **React Router**: Declarative routing for React applications.
- **Socket.io Client**: Real-time bidirectional event-based communication.

**Backend:**
- **Node.js & Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB & Mongoose**: NoSQL database for flexible data storage.
- **Socket.io**: Enables real-time, bidirectional and event-based communication.
- **JWT**: Securely transmitting information between parties as a JSON object.
- **Cloudinary**: Cloud-based image management services.
- **Arcjet**: Advanced security and rate limiting.

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (Local or Atlas)
- [Git](https://git-scm.com/)

## 🚀 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/zafor-hridoy/bengo-A-real-time-chat-Application.git
   cd Bengo
   ```

2. **Install Backend Dependencies:**

   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies:**

   ```bash
   cd ../frontend
   npm install
   ```

## 🔐 Environment Variables

Create a `.env` file in the **backend** directory and add the following:

```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

*(Note: Ensure you have your MongoDB URI and Cloudinary credentials ready)*

## ▶️ Running the Application

1. **Start the Backend Server:**

   ```bash
   cd backend
   npm start
   # or for development with nodemon
   npm run dev
   ```

2. **Start the Frontend Development Server:**

   Top open a new terminal:
   ```bash
   cd frontend
   npm run dev
   ```

3. **Open the App:**
   Visit `http://localhost:5173` (or the port shown in your terminal) to view the application.

## 📂 Project Structure

```
Bengo/
├── backend/            # Express backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   └── package.json
│
├── frontend/           # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
└── package.json        # Root package file
```

---
Made with ❤️ by [Zafor Hridoy]
