<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcaloab6y"/><path class="sssbgfhww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boarding-position" {...props}></Icon>
<style>
:global(.bcaloab6y) {
  d: path("M10 15H4.5a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2V13a2 2 0 0 1-2 2H14m-4 0V7h4v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sssbgfhww) {
  d: path("M3.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m14 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M2.5 21h19M11 18h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 21h-2a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11 18");
}

</style>
