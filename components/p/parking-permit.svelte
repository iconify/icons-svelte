<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sm5k18bje"/><path class="j_bxj6hfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-permit" {...props}></Icon>
<style>
:global(.j_bxj6hfe) {
  d: path("M10 18.5V10h3a2.5 2.5 0 0 1 0 5h-3");
}

:global(.sm5k18bje) {
  d: path("M5 7h14v14.5H5Zm7 0V4.25a1.75 1.75 0 0 1 3.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
