<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <style>
        body {
            background-color: #f0f0f0;
            color: #333;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #4CAF50;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Sample Page!</h1>
    <p>This is a simple example of a webpage hosted on GitHub.</p>
    <button id="clickMe">Click Me!</button>
    <p id="message"></p>
    <script>
        document.getElementById('clickMe').addEventListener('click', function() {
            document.getElementById('message').innerText = 'Hello! You clicked the button!';
        });
    </script>
</body>
</html>
