# Utiliser l'image officielle Node.js comme image de base
FROM node:latest
# Afficher un message dans le journal de construction
RUN echo "Hello World from Dockerfile"
# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier les fichiers de l'application Node.js dans le conteneur
COPY . .

# Installer les dépendances de l'application
RUN npm install

# Définir la commande par défaut pour exécuter l'application
CMD ["node", "app.js"]
