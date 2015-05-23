=============
Introducing M
=============
M is fun, and I want fun.

M is fun, but N is more fun.

Subtitle
========

Table of Contents
#################

.. toctree::
   :maxdepth: 2

   abstract
   introduction
 

:ref:`What languages can I use to develop mojits? <moj_langs>`  


.. topic:: Nice

    1. This is a paragraph.

    ::
   
       This is a code.

    2. I am done with block.
  

Code

.. code-block:: javascript

   [
     {
       "settings": [ "master" ],
       "specs": {
         "frame" : {
           "type" : "HTMLFrameMojit",
           "config": {
             "child" : {
               "type" : "framed"
             },
             "assets": {
               "top": {
                 "css": [
                   "/static/framed/assets/index.css"
                 ]
               }
             }
           }
         }
       }
     }
   ]


.. code-block:: javascript

   var state = "Alaska";
   console.log(state);



