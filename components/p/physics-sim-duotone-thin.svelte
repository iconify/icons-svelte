<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkci71b9o"/><path class="a2wn47b0j"/><path class="nl0jrlbgx"/><path class="myekf3bzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:physics-sim-duotone-thin" {...props}></Icon>
<style>
:global(.a2wn47b0j) {
  fill: currentColor;
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nl0jrlbgx) {
  d: path("M4 20 20 4v16Z");
}

:global(.tkci71b9o) {
  fill: currentColor;
  d: path("M4 20 20 4v16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
