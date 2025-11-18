# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>⚡ Marvel Studios Gallery ⚡</title>
  <style>
    body {
      font-family: "Cinzel", serif;
      margin: 0;
      padding: 0;
      color: white;
      text-align: center;
      background: 
        linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)),
        url("HPB.jpg") center center / cover no-repeat fixed;
    }

    .title {
      margin: 25px 0;
      font-size: 2.2em;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>
  <h1 class="title">⚡ Marvel Studios Gallery ⚡</h1>

  <div class="gallery">
    <a href="iron.jpg">
      <img src="iron.jpg" alt="Iron Man">
    </a>
    <a href="spy.jpg">
      <img src="spy.jpg" alt="SpiderMan">
    </a>
    <a href="thor.jpg">
      <img src="thor.jpg" alt="Thor">
    </a>
    <a href="captain.jpg">
      <img src="captain.jpg" alt="Captain America">
    </a>
    <a href="hulk.jpg">
      <img src="hulk.jpg" alt="Hulk">
    </a>
    <a href="doctor.jpg">
      <img src="doctor.jpg" alt="Doctor Strange">
    </a>
  </div>
</body>
</html>
```

## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/23e720b3-1183-4c62-9f49-d574649c25ee" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/857f8ea8-2d47-4bcf-af71-d1fab9d8ad8b" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/1bcd14cb-fd94-4aef-bc08-a54d18b68c28" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/5f7a6a22-3d07-4021-a316-609849e003e8" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/3786d44e-8f23-4954-a757-55642dd0bbeb" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f8a47122-7b8c-44c1-867f-c8408bc029e0" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/5839f8b3-320c-4a64-93dc-c28833233258" />








## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
