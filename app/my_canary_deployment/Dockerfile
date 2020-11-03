FROM python:3
RUN apt-get update -y
COPY . /app
WORKDIR /app
RUN pip install --no-cache-dir -r requirements.txt
CMD [ "python", "app.py" ]
