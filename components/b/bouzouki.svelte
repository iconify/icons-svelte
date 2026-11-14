<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t8q1d3irr"/><path class="e3c8sqb2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bouzouki" {...props}></Icon>
<style>
:global(.e3c8sqb2w) {
  d: path("M9.75 16a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.t8q1d3irr) {
  d: path("M10.5 10c-4.5 1-5.5 5-5 7.5c.5 3 3.5 4 6.5 4s6-1 6.5-4c.5-2.5-.5-6.5-5-7.5m-3 0V6.5L8.25 3l2.25-.75l3 4.25V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
