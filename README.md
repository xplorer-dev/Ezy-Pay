# Ezy-Pay

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/xplorer-dev/Ezy-Pay.git
Install Dependencies
bash
Copy code
npm install
Set Up PostgreSQL
Run PostgreSQL locally or use a cloud service like neon.tech.

Using Docker:
bash
Copy code
docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
Configure Environment Variables
Copy all .env.example files to .env.
Update .env files with the correct database URL.
Database Setup
Navigate to the packages/db directory and run:

bash
Copy code
npx prisma migrate dev
npx prisma db seed
Start the User Application
Navigate to the apps/user-app directory and run:

bash
Copy code
npm run dev
Test Login
Use the following credentials to log in:

Phone: 1111111111
Password: alice
