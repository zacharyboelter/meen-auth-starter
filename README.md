# meen-auth-starter
Authentication Template Repo

# Installation Instructions
Create a `.env` in the root of the project

Example `.env`:

```
PORT=3000
DATABASE_URL=mongodb+srv://yourUserName:yourPassword@cluster0.yjnfs.mongodb.net/meen-auth-starter?retryWrites=true&w=majority
SECRET=yourSecret
```
* npm i
* nodemon


* Users Create action --> Register a new user

* Sessions Create action ---> Creates cookie, logs a user in

* Sessions DESTROY (DELETE) action ---> Logs a user out. Deletes the cookie