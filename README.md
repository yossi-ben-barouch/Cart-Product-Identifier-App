# Cart-Product-Identifier-App 🛒

Cart-Product-Identifier-App based on CartAPP is an experimental learning application that allows users to take a picture with their phone, send the image to a backend API that queries an image processing model (such as OpenAI GPT-4), and receive an identification of the item in the picture along with its average price. This project serves as a learning exercise brought to us by @camilasandovals in our recent FloridaJS meetup (08/06/2024) to understand React Native, camera integration, and API interactions.

## Features

- **Camera Integration**: Users can take pictures using their phone's camera.
- **Image Upload**: The captured image is sent to a backend API for processing.
- **Item Identification**: The backend API processes the image and returns the identified item and its average price.
- **Shopping List**: Users can add identified items to their shopping list and view the total price.
- **Confirmation Modals**: Users receive confirmation prompts before adding or deleting items from the shopping list.

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [Node.js](https://nodejs.org/).
- **React Native CLI**: Install the React Native CLI globally using npm:
  ```bash
  npm install -g react-native-cli


### Installation

1.  **Clone the repository**:

    bash

    Copy code

    `git clone https://github.com/yourusername/Cart_Product_Identifier_React_FrontEnd.git

2.  **Install dependencies**:
3. 
    `yarn install`

3.  **Update API URL**: Open `App.js` and update the `API_URL` constant with your backend API URL:

    `const API_URL = "your_backend_api_url";`

4.  **Start the Metro bundler**:

    `npx react-native start`