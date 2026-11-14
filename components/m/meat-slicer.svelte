<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djn-6pd6f"/><path class="hbfpy5vnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:meat-slicer" {...props}></Icon>
<style>
:global(.djn-6pd6f) {
  d: path("M4.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.hbfpy5vnz) {
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 21h18M7 18.5V21m10-2.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
