# YouTube Clone: Full-Stack Application

## Main Functionalities

The YouTube clone offers a range of functionalities for users:

- **List Videos:** Explore a curated collection of videos available on the platform.
- **Watch a Video:** Seamlessly enjoy video content within the interface.
- **Sign In/Out:** Access personalized features with user authentication.
- **Upload a Video:** Contribute content to the platform's library.
- **Watch Transcoded Video:** Experience optimized video playback with transcoded content.

## Tech Stack

The application leverages a robust technology stack for efficient performance:

- **TypeScript:** Ensures strong typing and scalability for the codebase.
- **Next.js:** Powers the frontend interface with efficient server-side rendering.
- **Express.js:** Facilitates backend development with a minimalist web framework.
- **Docker:** Enables containerization for streamlined deployment across environments.
- **FFmpeg:** Handles video transcoding and processing tasks efficiently.
- **Firebase Auth:** Manages user authentication and access control seamlessly.
- **Firebase Functions:** Implements serverless functions to support backend logic.
- **Firebase Firestore:** Stores metadata and user data in a scalable NoSQL database.
- **Google Cloud Storage:** Offers reliable storage solutions for videos and assets.
- **Google Cloud Pub/Sub:** Facilitates messaging between different components of the application.
- **Google Cloud Run:** Hosts application services in a scalable and managed environment.

## Architecture

The application architecture is designed for efficiency and scalability:

- **Cloud Storage:** Stores both raw and processed videos uploaded by users.
- **Pub/Sub:** Facilitates message passing to trigger video processing tasks.
- **Cloud Run:** Hosts the video processing service, ensuring efficient transcoding and storage.
- **Cloud Firestore:** Manages metadata and user-related data for efficient retrieval and storage.
- **Next.js App:** Serves as the frontend interface for users, making API calls to Firebase Functions.
- **Firebase Functions:** Handles backend logic, fetching videos from Firestore and serving them to the frontend.

<img width="1152" alt="Screenshot 2024-03-10 at 4 22 22 PM" src="https://github.com/yesh07/YouTube-clone/assets/60771818/51e90d69-5dcf-47d4-a620-663533fdaef1">
