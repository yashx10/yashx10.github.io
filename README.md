<!DOCTYPE html>
<html>
  <head>
    <title>Advanced Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      /* Responsive design */
      @media (max-width: 600px) {
        .grid-container {
          grid-template-columns: 1fr;
        }
      }

      /* CSS Grid layout */
      .grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 10px;
        padding: 10px;
      }

      /* Navigation bar */
      .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #333;
        color: #fff;
        padding: 10px;
        position: sticky;
        top: 0;
        z-index: 1;
      }

      .navbar a {
        color: #fff;
        text-decoration: none;
        margin-right: 10px;
      }

      /* Other styles */
      .grid-item {
        background-color: #fff;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <div class="navbar">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>
    <div class="grid-container">
      <div class="grid-item">
        <h2>Section 1</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna euismod egestas congue, augue magna pharetra nibh, id convallis nisl nisi id magna.</p>
      </div>
      <div class="grid-item">
        <h2>Section 2</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna euismod egestas congue, augue magna pharetra nibh, id convallis nisl nisi id magna.</p>
      </div>
      <div class="grid-item">
        <h2>Section 3</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna euismod egestas congue, augue magna pharetra nibh, id convallis nisl nisi id magna.</p>
      </div>
    </div>
  </body>
</html>
