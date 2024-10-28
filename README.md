# New App

## Overview

New App is a SolidJS application that allows users aged 18 and above to explore and interact with jokes in various ways. Users can sign in using ZAPT authentication, add new jokes, generate jokes, create joke-related images, convert jokes to speech, and generate markdown stories.

## User Journeys

### 1. User Sign-In

1. The user opens the app and sees a sign-in page titled "Sign in with ZAPT".
2. The user can learn more about ZAPT via a link to the [ZAPT website](https://www.zapt.ai).
3. The user signs in using one of the available methods:
   - Email (Magic Link)
   - Google
   - Facebook
   - Apple

### 2. Age Confirmation

1. Upon successful sign-in, the user is presented with an age confirmation message:
   - "The features of this app are intended for users aged 18 and above."
2. The user clicks the button "I confirm that I am over 18" to proceed.
3. If the user does not confirm, they cannot access the app features.

### 3. Adding a New Joke

1. The user accesses the "Add New Joke" section.
2. The user fills in the "Setup" and "Punchline" fields.
3. The user clicks the "Save Joke" button.
4. The joke is saved, and the joke list is updated.

### 4. Generating a Joke

1. The user clicks the "Generate Joke" button.
2. The app generates a new joke using AI and fills the "Setup" and "Punchline" fields.
3. The user can save the generated joke by clicking "Save Joke".

### 5. Viewing Jokes

1. The user navigates to the "Joke List" section.
2. The user can scroll through the list of saved jokes.
3. Each joke displays its setup and punchline.

### 6. Additional Features

#### Generate Image

1. The user clicks the "Generate Image" button.
2. The app generates an image related to jokes.
3. The generated image is displayed in the "Generated Image" section.

#### Text to Speech

1. The user ensures there is a joke in the "Setup" and "Punchline" fields.
2. The user clicks the "Text to Speech" button.
3. The app converts the joke into an audio file.
4. The audio player appears, allowing the user to play the joke.

#### Generate Markdown Story

1. The user clicks the "Generate Markdown" button.
2. The app generates a funny story in markdown format.
3. The story is displayed, formatted appropriately.

### 7. Signing Out

1. The user clicks the "Sign Out" button at the top of the page.
2. The user is signed out and returned to the sign-in page.

## External API Services Used

- **ZAPT**: Used for user authentication and event handling.
- **AI Services**: Used to generate jokes, images, text-to-speech audio, and markdown stories.

## Requirements

- Users must be 18 years or older to access the app features.
- Users need to sign in using ZAPT authentication.
