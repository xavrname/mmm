git clone <URL-del-repositorio>
cd <nombre-del-repositorio>
git checkout develop
git checkout -b feature/agregar-ana
git add index.html
git commit -m "Agregar nombre Ana Rodríguez al listado"
git push origin feature/agregar-ana
git checkout develop
git pull origin develop
git checkout main
git merge develop
git push origin main
