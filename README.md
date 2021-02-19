# Smart-brain

## An App which you can detect your face within an image.

Feel free to try yourself and play with the app. url:https://smart-brain-freddy.herokuapp.com

## Features
✔️ Full Stack Development
✔️ React Framework used for Front-End
✔️ Node.js + Express.js used for Back-End
✔️ PostgreSQL used for Database
✔️ Built with tachyons and Custom CSS\
✔️ Light Clean Codes\
✔️ Fully Responsive\
✔️ Valid HTML5 & CSS3\

---
## Getting Started 🚀

First acces in the website, there is a sign in form and a register form. We collect user information and store them in the database. After login the website, a block requires a image url for face detection. you can paste an image ends with .jpg, and it will show a box which indicates the location of the face in the image. It also counts the image detect times that a user has done, and store in the database.

## API Selection

I choose to use Clarifai face recognition API (url:https://www.clarifai.com/models/face-detection), it is easy to use and understand. The request of this api is an image url, and the response is called "bounding_box" values, which are the coordinates of the box outlining each face within the image. For the blue box shown in the image detection result is a CSS pixel calculation.

## Why React?

React is an Front-End Frameworrk, and it has many advantages such as modulized components, easy maintenance, etc. Most important, it is easy to pick up and is popular throughout recent front-end environment (Vue.js is like an elevator with nowadays). For the above reasons, I choose to use React for this practice project.

