<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tt7ypiikb"/><path class="zgod0v2rr"/><path class="du3agkbjb"/><path class="nj6hdwb2d"/><path class="olmwgycdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:branch-git-outline-thin" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nj6hdwb2d) {
  d: path("M7 12h7.5");
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tt7ypiikb) {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zgod0v2rr) {
  d: path("M7 8.5v7");
}

</style>
