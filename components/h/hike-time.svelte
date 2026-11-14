<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bj1h9z9us"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hike-time" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.bj1h9z9us) {
  d: path("M3.5 21c6.5 0 6.5-5.5 3-8S5 5.5 11 6.5c4 .75 5-2.5 9.5-3M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
