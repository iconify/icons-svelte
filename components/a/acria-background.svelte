<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="scequ2bfg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:acria-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.scequ2bfg) {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.5 11.25H8.25l3.75-6l4.75 8.5h-7.5l-1.75 3h1.75l1.5-2.5h2.5l1.5 2.5h2l-1.5-2.5h2l2.75 4.5h-6.5l-1.5-3l-1.5 3H4l4-7h5.5l-1.5-3z");
}

</style>
