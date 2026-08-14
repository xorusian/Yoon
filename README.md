# Yoonfrom flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return """
    <html>
    <head>
        <meta charset="UTF-8">
        <title>Message</title>
    </head>
    <body style="text-align:center; margin-top:150px;">
        <h1>ကလေးမရည်းစားမထားနဲ့</h1>
    </body>
    </html>
    """

app.run(host="0.0.0.0", port=5000)
