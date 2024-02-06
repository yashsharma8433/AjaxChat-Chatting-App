<br />
  <h1 align="center">Chat-app 🧑🏼‍💻</h1>

  <p align="center">
    A chat app built with Node.js, Socket.io, React.js, and Tailwind CSS.
    <br />
    <br />
 
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

![Chat-app🦜](Screenshot.png)

A real-time app to exchange messages with connected users. Built for learning purposes. This was the first time using **Socket.io**, so I decided to follow their tutorial to create a chat app and I added a few of the suggested features.

### Built With

- Node.js
- Socket.io
- React.js
- Tailwind CSS

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You need to have npm installed.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone 
   ```
2. From the root, install NPM packages
   ```sh
   npm install
   ```
3. From the CLIENT directory, install NPM packages
   ```sh
   npm install
   ```
4. Run the project using this command:
   ```sh
   npm run dev
   ```

### Deploy (Example using Heroku)

- uncomment lines 10-13 from "server.js"
  ```sh
   // app.use(express.static(path.join(__dirname, "client/build")));
   // app.get("/*", function (req, res) {
   //   res.sendFile(path.join(__dirname, "client/build", "index.html"));
   // });
  ```
## Features

- Support for nickname
- Message to connected users when someone connects or disconnects
- List with online users
- Private messages
- Mobile friendly



