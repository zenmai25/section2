# kodego-music-player
Project Structure:
The project structure for this app is:
The root folder has a public sub-folder which contains the html, css and javascript files for this project. It also contains the audio and image files that were used in this project. Each of them has a folder of their own. Except for the javascript script, because it's inside the html file of this project. I have used node.js for this project. I used it for the api endpoints. And so I have a server.js file on the root-folder(kodego-music-player) as well.
---
Compromises & Such:
Because of time constraints, I have focused on the functionality of the app. With more time, I would like to improve the design and ui of my music player app. I wanted to use codepen.io for my solution... but it seems like I can't use node.js in this platform. So I chose to use Github to present my solution instead, since my app is using node.js. 
I also wasn't able to use the API from Rapid API because it was fetching the lyrics from a different song. I tried to read the documentation but the API didn't have any. I tried fetching the lyrics for the song through the API site of Lyrics Genius but I can't find the song id for the song. The same with the other albums and related artists. I tried fetching them from the Spotify API but the process was kind of complicated. There was an error that I can't fix. I would have stayed with it longer if I had more time. But I also have to consider the other sections of the technical exam. I need to alot time for them as well. So given the the time constraints, I decided to create my own API endpoints for fetching the lyrics, the other albums and related artists.
---
Error Cases & Such:
The app doesn't have unhandled errors.
---
How To Access This App/ Locally:
1. Clone this app/game in your Github Desktop. You can also download it as a zip file if you prefer that method.
2. After cloning/downloading the zip file, open it in VS Code.
2.1. If you chose to download it as a zip file, make sure to extract it first, then open it in VS Code.
3. After opening the file in VS Code, open a new terminal (in VS Code). On the terminal, write this command: npm install. Press Enter. Wait for the installing process to be done. After that, write this command on the same terminal: npm run dev. Press Enter. Wait for a few seconds, then this message will show on the terminal 'Server is running on port 3000'. Open your browser and go to: http://localhost:3000/.
---
How to Access the Deployed Version of this App:
1. Just go this link: https://music-player-mg81.onrender.com/
---
Notes:
1. To play the next song, click the pause button first, then click the next or previous button. Then click the play button after that.
2. The items in the 'Other Albums' section and 'Related Artists' section are clickable. If you click them, they will redirect you to the spotify link/playlist of the said albums and artists.
3. My solutions for sections 1 and 2 of the technical exam are in one codebase/file/folder.
