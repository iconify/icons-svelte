<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-9o9hyeb"/><path class="teqvyu0hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carousel-arrows" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-9o9hyeb) {
  d: path("M4.25 9L2.5 12l1.75 3m15.5-6l1.75 3l-1.75 3");
}

:global(.teqvyu0hf) {
  fill: currentColor;
  d: path("M6.75 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m4 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
