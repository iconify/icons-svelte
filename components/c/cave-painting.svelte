<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oz6nz8bhr"/><path class="b375pibmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cave-painting" {...props}></Icon>
<style>
:global(.b375pibmz) {
  d: path("M8.5 8v7.5c0 2.5 1.75 4 4 4s4.25-1.5 4.25-4V10m-5.5-3.5V13M14 7v6m-8.25-.5l2.75 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oz6nz8bhr) {
  d: path("M2.5 21v-9.5a9.5 8.5 0 0 1 19 0V21");
}

</style>
