<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr2v8wb3d"/><path class="q-ag8yb9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-pet-toys" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q-ag8yb9q) {
  d: path("M3 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m15-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.xr2v8wb3d) {
  d: path("M4 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-8 0h8");
}

</style>
