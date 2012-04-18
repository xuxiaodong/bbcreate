bbcreate - Create a Bitbucket repository from the command line.

### Configuration

Open ~/.hgrc, then add the following lines:

    [auth]
    bb.prefix   = bitbucket.org/your_user_name/
    bb.username = your_user_name
    bb.password = your_password
    bb.schemes  = http https

### Usage

   % bbcreate -n <name> [-d <desc>] -s <scm> [-p]
   
   -n, --name name         Repository name
   -d, --desc description  Project description
   -s, --scm  scm          Repository type
   -p, --priv private      Set repository as private
