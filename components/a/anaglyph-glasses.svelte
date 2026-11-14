<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-q0e_bdd"/><path class="oav10h6ck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:anaglyph-glasses" {...props}></Icon>
<style>
:global(.h-q0e_bdd) {
  fill: currentColor;
  d: path("M3 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.oav10h6ck) {
  d: path("M13 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 9h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
