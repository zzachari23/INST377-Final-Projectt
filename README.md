# INST377-Final-Project
## Project Title: Official NBA Statistics 
## Group: Project Group 3
## Names: Sarah Peng, Shengjie Liu, Zachariah Zachariah
## Description of project: 

The goal of our project is to create a platform that aims to provide a user-friendly and visually appealing way to access NBA statistics for people in fantasy leagues and sports betting. We understand that it can be overwhelming to navigate through the vast amount of data available, so we have designed our platform to make it easy for users to search for specific players or teams and compare their stats based on different criteria. To achieve this, we use graphs and images to visualize the data, making it easier for users to understand and interpret the information. For example, the user has the options to create bar and line graphs to compare the average points per game for a specific season year between 5 user picked NBA players. We were able to create the graphs by making use of the Javascript Chart.js library. In addition, the user also has the option to use a team map to show the different teams across the country just by clicking the region representing the team and that will provide the user API fetched information about the chosen team. Furthermore, our platform is not only useful for people in fantasy leagues or sports betting, but also for sponsors and the NBA in general. By providing a comprehensive and easy-to-use platform for accessing NBA statistics, we hope to contribute to the growth and success of the league.

In terms of the API we chose, we chose The BALLDONTLIE API which is a platform that provides NBA team and individual player statistics. The reason we chose this API is because we wanted to help sports betters and those who engage in NBA fantasy leagues make more informed and logical decisions. By using this API, we can provide our users with accurate and up-to-date information that can help them make better decisions.

Link to API: https://app.balldontlie.io/

To display this information, we will be styling our web pages using HTML and CSS. We have also used page transition animations, gifs, and custom styled CSS buttons that we aquired from online sources but have personalized/modified them to make them more aligned with our platform's visual asthetics. Additionally, we will be using Javascript to fetch the API using the FETCH method. This will allow us to retrieve the data we need and display it in a user-friendly way. Our platoform, also makes use of Express as our Javascript Framework using Node.js which handles the backend and server-side of our application. Lastly, our platform makes use of a Supabase database that contains tables that provide critical NBA player and teams stats for users. In addition, the user can also insert information into the database as well. 

## Description of target browsers: 

# Developer Manual

## How to install application and all dependencies
1. First git clone the repository files to your local computer. This can be done by clicking the "Code" button on the repo page. Once you click the button, you can git clone by using either HTTPS, SSH or GitHub CLI. For Mac users, you can open up the terminal and type in 'git clone [Insrt SSH Link]' and it will download the repo files as one folder to your desired local computer directory.
2. Install Node Version Manager (nvm) to your local computer so that we can use nvm to install Node.js. Link to step-by-step guide on installing nvm: https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/
3. Open up terminal and type (for MAC users) npm -v to check to see what version of npm you installed. npm stands for Node Packet Manager which automatically comes with Node.js when you install node via nvm
4. Make sure the Supabase package is installed in your local project directory to ensure that the code for using the Supabase database works. This can be done by opening up terminal for MAC users and typing 'npm install @supabase/supabase-js'
## How to run application on server
1.To start running the application on a local server, for MAC users open up terminal and type in 'npm start'
2.To stop the 
## How to run any tests you have written for your software 
## The A
## A clear set of expectations around known bugs and a road-map for future development 



- Install dependencies (do this after you clone the repo): npm i
- Start the web application: npm start
- Stop the web application: CTRL + C in your terminal
