# Next.js Starter Project

This is a starter project for React that uses Next.js.
* Comes with Ionicons icon font and shows how to bundle other CSS and font files

You can see a live demo at **https://imdb.100jsprojects.com/**
![image](https://github.com/zxc-daun/imdb-next/assets/102352117/50a92330-aa41-4d5b-a188-a5a48aafa62e)

## About 

Next.js is a framework that makes it easy to create 'universal' React apps - React apps that do both client and server side rendering.

With Next.js, React pages are automatically rendered on both client and server side, without the hassle of setting up dependancies like webpack or babel and with automatic routing and without the constraints of projects like Create React App.

This is a starter project that provides an example of how to use Next.js, the Ionicons icon set, examples of how to include data from remote APIs.

This project exists to make it easier to get started a creating production app in React. You are invited to use it as a reference or to copy it and use it as a base for your own projects. Contributions to improve this project are welcome.

## Running locally in development mode
![image](https://github.com/zxc-daun/imdb-next/assets/102352117/d43b6eec-f002-45dc-94f3-ff5c0233bb0c)

To get started, just clone the repository and run `npm install && npm run dev`:

    git clone https://github.com/zxc-daun/x-next
    npm install
    npm run dev

Note: If you are running on Windows run install --noptional flag (i.e. `npm install --no-optional`) which will skip installing fsevents.

## Building and deploying in production

If you wanted to run this site in production, you should install modules then build the site with `npm run build` and run it with `npm start`:

    npm install
    npm run build
    npm start

You should run `npm run build` again any time you make changes to the site.

Note: If you are already running a webserver on port 80 (e.g. Macs usually have the Apache webserver running on port 80) you can still start the example in production mode by passing a different port as an Environment Variable when starting (e.g. `PORT=3000 npm start`).

----

## Further reading


### Secrets for Environment Variables

Once you are comfortable using `.env` files for configuration and running and deploying your app, take a look at `now secrets` to set options in the cloud so you don't have to set them each time you deploy.

### GitHub integration

You can integrate `now` with a GitHub account to trigger automated deployments anytime you push to GitHub. This works great if you have secrets set up!

### Alternate hosting options

You can host your Next.js site with any hosting provider. Although it works great on Now, it also works great with other providers like Heroku, Amazon Web Service, Google Cloud Platform, Microsoft Azure, DigitalOcean and others.
