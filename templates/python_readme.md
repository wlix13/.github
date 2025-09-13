> [!WARNING]
> We **only** support the `uv` installation method. Other tools, such as `conda`
> or `pip`, don't provide any guarantees that they will install the correct
> dependency versions. You will almost certainly have _random bugs, error messages,_, and other problems if you don't use `uv`.
> Please _do not report any issues_ if you use non-standard installations, since almost all such issues are invalid.
>
> Furthermore, `uv` is [up to 115x faster](https://github.com/astral-sh/uv/blob/main/BENCHMARKS.md)
> than `pip`, which is another _great_ reason to embrace the new industry-standard
> for Python project management.

> [!TIP]
> **Quick & Easy Installation Method:**
>
> There are many convenient ways to install the uv command on your computer. Please check the link below to see all options.
>
> [Installation Guide](https://docs.astral.sh/uv/getting-started/installation/)
>
> Alternatively, if you want a very quick and easy method, you can install it as follows:
>
> ```bash
> pip install -U uv
> ```
