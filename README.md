# AudioPlayer
AudioPlayer is application which with help of Mixcloud API, provides way for users to search Mixcloud music by users, tags and title of upload. Also users are able to upload audio and image for this audio and edit it. Also as main functionality to play music via embeded Mixcloud player.

Built With
 - JavaScript or TypeScript (here I'm leaving for whole team to decide)
 - React
 - Redux or Mobx (here I'm leaving for whole team to decide)
 - Bulma? (here I'm leaving for whole team to decide as I'm not sure if we want to use any css framework)

Main Functionality
 - Search input field, which search for Mixcloud users, tracks by title and by tags.
 - User can add own song by uploading mp3 file which can't be bigger than 524288000 bytes. When adding song user is able to
   upload image for this song which cant be bigger than 10485760 bytes. Along side with uploaded files is possible to provied    title (which is required), description (max 1000 characters) and max 5 tags which will help to categorize uploaded audio.
 - Validation if uploaded files are in the correct format also validation if provided description and title are acceptable.
 - Is possible to choose audio and then play with usage of Mixcloud embeded player. Where application will provide Mixcloud user name and track name, and will get back html with iframe for choosed song.

