FROM python:3.9-slim-bullseye
WORKDIR /app
#ENV APP_PATH=services/worker
COPY . .
RUN pip install -r /app/services/worker/requirements.txt

CMD ["python3", "services/worker/app.py"]

#CMD ["python3", "app.py"]
#*-