<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wgq2vpjgt"/><path class="t-uel1djz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crochet-amigurumi" {...props}></Icon>
<style>
:global(.t-uel1djz) {
  d: path("M5 9a2.5 2.5 0 1 1 3.5-3.25m7 0A2.5 2.5 0 1 1 19 9M9 13h.01M15 13h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wgq2vpjgt) {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

</style>
