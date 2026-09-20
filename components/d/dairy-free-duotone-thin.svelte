<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bc503ub0k"/><path class="c8h3t-z9z"/><path class="y80g12bwz"/><path class="jbmfbdcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dairy-free-duotone-thin" {...props}></Icon>
<style>
:global(.bc503ub0k) {
  fill: currentColor;
  d: path("M7 9v11h9V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c8h3t-z9z) {
  d: path("M7 9v11h9V9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jbmfbdcwk) {
  d: path("M4 21 20 5");
}

:global(.y80g12bwz) {
  d: path("m7 9 4.5 -4.5L16 9");
}

</style>
