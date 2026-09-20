<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="gc63x_bnw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mtl-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gc63x_bnw) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5h1v14H4zm5 3h1v9H9zm5 2h1v5h-1zm5-5h1v14h-1z");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
