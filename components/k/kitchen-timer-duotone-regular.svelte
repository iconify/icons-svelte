<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tdwzb1a8u"/><path class="dr_svztcl"/><path class="g7fe9zb5k"/><path class="ays356bvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kitchen-timer-duotone-regular" {...props}></Icon>
<style>
:global(.ays356bvr) {
  d: path("m12 14 3 -3");
}

:global(.dr_svztcl) {
  d: path("M5.5 14a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

:global(.g7fe9zb5k) {
  d: path("M10 7.5V4h4v3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tdwzb1a8u) {
  fill: currentColor;
  d: path("M5.5 14a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
