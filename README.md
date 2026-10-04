# obfuscator

run python3 obfuscator.py

this is sorta useful for byp#ssing filter ais since it obfuscates the actual varibles into random strings by defualt its Scramjet but you can change it ex for UV you would change 

 ```
unified_token_registry = {
        "scramjet": generate_valid_js_identifier(),
        "baremux":  generate_valid_js_identifier(),
        "bare-mux": generate_valid_js_identifier(),
        "mercuryworkshop": generate_valid_js_identifier(),
    }
  ```
to


   

    unified_token_registry = {
        "ultraviolet": generate_valid_js_identifier(),
        "baremux":  generate_valid_js_identifier(),
        "bare-mux":  generate_valid_js_identifier(),
        "inject": generate_valid_js_identifier(),
        "rewrite": generate_valid_js_identifier(),
        "uv": generate_valid_js_identifier(),
        "titaniumnetwork": generate_valid_js_identifier(),
    }

  or for SJ v2 it would just be 
   ```
unified_token_registry = {
        "scramjet": generate_valid_js_identifier(),
        "scramjetcontroller":  generate_valid_js_identifier(),
        "cookiejar": generate_valid_js_identifier(),
        "mercuryworkshop": generate_valid_js_identifier(),
    }
  ```


  and change the target_folders = ["scram", "public", "baremux"]
    to whereever your proxy assets are at



