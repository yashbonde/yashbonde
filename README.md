### Hi there 👋

My name is Yash Bonde, AI researcher. Get to know more at [KS2Labs](https://github.com/ks2labs) and [NimbleBox.ai](https://github.com/NimbleBoxAI). I am currently experimenting with streaming my work, watch it on [YouTube](https://www.youtube.com/playlist?list=PLDwlXbwbl9GN4byp44SmqzrRGwHNbUqg3).

**Experience**: Worked in all domains of deep learning CV, NLP, Documents, Audio and now working in RL and industry applied AI. I regularly [blog](https://yashbonde.github.io/musings.html) on topics that interest me. Open for freelancing gigs, connect on my [LinkedIn](https://www.linkedin.com/in/yash-bonde/).

**Gists**: Over the years, I think gists are what will define human.

- `62df9d16858a43775c22a6af00a8d707` I have a bunch of functions I use everyday, [daily.py](https://gist.github.com/yashbonde/62df9d16858a43775c22a6af00a8d707)
- `cadb515b6c658f18147d948fac685c7b` Make GPT generation chill, [gpt.py](https://gist.github.com/yashbonde/cadb515b6c658f18147d948fac685c7b)

How to get any gist:

```python
def get_gist(id):
  import requests, json
  d = json.loads(requests.get(f"https://api.github.com/gists/{id}").content.decode("utf-8"))
  for file_name in d["files"]: # save all the files exactly like on your gist
    with open(file_name, "w") as f:
      print("Writing:", file_name)
      f.write(d["files"][file_name]["content"])
        
get_gist(id_from_above)
```

<hr>

Here is a meme on AI

<img src="https://i.imgur.com/NFe4C3U.jpg" height=400px>
<!-- <img src="https://memeguy.com/photos/images/what-ai-actually-is-327606.jpg" height=400px> -->
