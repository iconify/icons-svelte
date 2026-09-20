<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b07kex9cp"/><path class="fxgpgno0d"/><path class="thp6nvbvl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:kilt-background" {...props}></Icon>
<style>
:global(.b07kex9cp) {
  fill: var(--svg-color--8c175b, #8c175b);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.fxgpgno0d) {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.5 4h3v9.6l-.75-1.6l.75 3.975V20h-3z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.thp6nvbvl) {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.93 4H18l-3.93 7H11zm-.265 16H18l-4.285-8H10.5zm-8.2-9h11.07c.26 0 .465.23.465.5c0 .28-.215.5-.465.5H6.465c-.26 0-.465-.23-.465-.5s.215-.5.465-.5");
}

</style>
