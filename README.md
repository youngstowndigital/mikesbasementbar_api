# Mikes Basement Bar API

This is the API/Backend for Mikes Basement Bar Website. It was built using StrapiJS (https://strapi.io/), an open source headless CMS solution.

## Installation

cd into the root of the repo and run:

`
yarn install
`

Create a .env file with the following variables for AWS S3 integration for file uploads:

`
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
AWS_BUCKET_NAME=
`

## Run Locally

cd into the root of the repo and run:

`
yarn develop
`

- Local database is created
- Setup an adminstrator account from the /admin page
- Make any changes to the api from the administrator screens

## CI/CD

Test and Prod environments are on heroku

- Remote repository has a 'test' branch which is hooked up to the test heroku app
- Remote repository has a 'main' branch which is hooked up to the prod heroku app
