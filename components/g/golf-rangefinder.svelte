<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pkag1cbnc"/><path class="gif1hdbdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-rangefinder" {...props}></Icon>
<style>
:global(.gif1hdbdk) {
  d: path("M13 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 0h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pkag1cbnc) {
  d: path("M2.5 9.5h4l3-3h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-10l-3-3h-4Z");
}

</style>
