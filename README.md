# learning-log-web-app-django
This is a project developed with Django and HTML aiming to produce a simple web app. The name of the web app is learning log. It is based on the third hands-on project in "Python Crash Course" book by Eric Matthes. The core of my code follows the lines of code shown in the book, nevertheless, my main contributions to this project are: (1) redirect every user to the topics page once they logged in, (2) add a delete button that allows deleting entries, (3) style the register page accordingly to the style used for the other pages, (4) show the topics button only if the user is authenticated, and (5) prevent the common attack of a user adding a new entry to another user's account by checking that the topic owner is the same as the user that is requesting this action. The main structure of this repository is organized in three folders:

1. learning_log = project
2. learning_logs = app
3. users = app
