<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wl0ht0yem"/><path class="fim5wvb3d"/><path class="j5z_xpbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:active-passive-outline-regular" {...props}></Icon>
<style>
:global(.fim5wvb3d) {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.j5z_xpbsk) {
  d: path("M13.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wl0ht0yem) {
  d: path("M2.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
