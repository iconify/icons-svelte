<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sppcq7_is"/><path class="ip433c35j"/><path class="vs7anegma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:docking" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ip433c35j) {
  d: path("M10.25 16a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0M5.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.sppcq7_is) {
  d: path("M2.25 8a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

:global(.vs7anegma) {
  d: path("M13.5 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
