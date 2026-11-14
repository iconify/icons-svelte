<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hucymkb5k"/><path class="uz3c2ub6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:centrifugal-pump" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hucymkb5k) {
  d: path("M5 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.uz3c2ub6a) {
  d: path("M13.5 8V3h4v8M4 21.5h14m-9-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
