<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r24qptfib"/><path class="u4godzowz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aggregate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r24qptfib) {
  fill: currentColor;
  d: path("M17.25 10h2.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 19.75 14h-2.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 17.25 10");
}

:global(.u4godzowz) {
  d: path("M9.5 4.5c1.5 0 2 .75 2 2.25v3c0 1.5.5 2.25 1.75 2.25c-1.25 0-1.75.75-1.75 2.25v3c0 1.5-.5 2.25-2 2.25M2.5 6H7m-4.5 6H7m-4.5 6H7");
}

</style>
