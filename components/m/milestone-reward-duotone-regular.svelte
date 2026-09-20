<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wmn-8gkkk"/><path class="lsng_0odv"/><path class="e3g_5gbjc"/><path class="adxensbci"/><path class="nrad3_umv"/><path class="tl2fjsrpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milestone-reward-duotone-regular" {...props}></Icon>
<style>
:global(.adxensbci) {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

:global(.e3g_5gbjc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 9 2.5 2.5L14.5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lsng_0odv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrad3_umv) {
  d: path("M10 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tl2fjsrpp) {
  d: path("m9.5 9 2.5 2.5L14.5 9");
}

:global(.wmn-8gkkk) {
  fill: currentColor;
  d: path("M10 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
