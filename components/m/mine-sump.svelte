<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q1b96s9zw"/><path class="atxkqdb3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mine-sump" {...props}></Icon>
<style>
:global(.atxkqdb3o) {
  d: path("M6 14.5q3-2 6 0t6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1b96s9zw) {
  d: path("M2.5 5H6v14h12V5h3.5");
}

</style>
