<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flmpe8bon"/><path class="x68x1ib8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:disease-rot" {...props}></Icon>
<style>
:global(.flmpe8bon) {
  d: path("M6 5c9-1 15 6 13.5 16C10 20 4.5 14 6 5M3.5 2.75L6 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x68x1ib8m) {
  d: path("M9 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.5 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
