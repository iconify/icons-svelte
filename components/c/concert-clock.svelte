<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eh27bb1bt"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:concert-clock" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.eh27bb1bt) {
  d: path("M4.5 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0V3m0 0q4 1 5.5 5.5M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
