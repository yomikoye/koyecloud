## Develop Locally

1. Install dependencies

       npm install
       
2. Start the Next.js local development server:

        npm run develop

3. Open [http://localhost:3000/](http://localhost:3000/) in the browser to see
   your site. You can now edit the site contents, and the browser will
   live-update your changes. 🎉


## Building for production 🏗

To build a static site for production, or test locally how it works, run the
following command:

    npm run build

The exported site will be written to `out` folder. The contents of this folder 
can be deployed by serverless deployment platform such as [Netlify](https://www.netlify.com).
You can start a local server serving the static files from the `out` folder, for
example by installing and running `http-server`:

    npm install http-server -g
    http-server out

[![Netlify Status](https://api.netlify.com/api/v1/badges/a53181b0-a375-4981-b4f9-0ab55a4cf428/deploy-status)](https://app.netlify.com/sites/kind-heisenberg-a85572/deploys)
