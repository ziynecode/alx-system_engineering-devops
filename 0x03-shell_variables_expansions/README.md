Welcome to my readme file 

note that this file contains code to run certain tasks
0. vi 0-alias

         Press i to insert

then type

#!/bin/bash

0-alias ls='rm *'


after that press Esc key on your keyboard and type :wq then hit enter button


then chmod u+x 0-alias

and git add .

commmit

and push


make sure u do it in all the task


1. vi 1-hello_you

        #!/bin/bash

        echo "hello $USER"


2. vi 2-path

        #!/bin/bash

        PATH=$PATH:/action


3.vi 3-paths

        #!/bin/bash

        echo $PATH | tr ':' '\n' | wc -l


4. vi 4-global_variables

        #!/bin/bash

        printenv


5. vi 5-local_variables

        #!/bin/bash

        set

        

6. vi 6-create_local_variable

        #!/bin/bash

        BEST="School"


7. vi 7-create_global_variable

        #!/bin/bash

        export BEST="School"


8. vi 8-true_knowledge

        #!/bin/bash

        echo $((128+ $TRUEKNOWLEDGE))


9. vi 9-divide_and_rule

        #!/bin/bash

        echo $(($POWER/$DIVIDE))


10. vi 10-love_exponent_breath

        #!/bin/bash

        echo $(($BREATH**$LOVE))


11. vi 11-binary_to_decimal

        #!/bin/bash

        echo $((2#$BINARY))


12. vi 12-combinations

        #!/bin/bash

        echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"


13. vi 13-print_float

        #!/bin/bash

        printf '%.2f\n' $NUM
