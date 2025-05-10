# Speech-to-Text Platform with User Registration

This project is a web application built using *Flask* that allows users to upload audio files and converts them into text. It also includes a user registration and authentication system. Users can register, log in, and access the speech-to-text service.

## Features

- *User Registration & Authentication*: Users can sign up, log in, and manage their profiles.
- *Speech-to-Text Conversion*: Users can upload audio files (e.g., WAV, MP3) for transcription.
- *History*: Users can view the history of their uploaded files and the corresponding transcriptions.
- *API Endpoints*: Exposes RESTful API endpoints to interact with the application programmatically.
- *Flask & SQLAlchemy*: The application uses Flask as the web framework and SQLAlchemy as the ORM for database management.

## Technologies Used

- *Flask*: Web framework for building the application.
- *Flask-RESTful*: For building the RESTful API.
- *SQLAlchemy*: For managing the database.
- *SpeechRecognition*: Python library to convert speech to text.
- *SQLite/PostgreSQL*: Database for storing user and file data.
- *Docker*: For containerizing the application.

## Project Setup

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/yasorefaai1245/speech-to-text-flask.git
cd speech-to-text-flask