<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcm12vbdr"/><path class="v3mivhbeb"/><path class="pcl5pkbcw"/><path class="votyijv0m"/><path class="tlwdv3zao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baking-duotone-thin" {...props}></Icon>
<style>
:global(.gcm12vbdr) {
  fill: currentColor;
  d: path("M5 9a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3");
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

:global(.pcl5pkbcw) {
  d: path("M2 9h3");
}

:global(.tlwdv3zao) {
  d: path("M4 20c3 -3 13 -3 16 0");
}

:global(.v3mivhbeb) {
  d: path("M5 9a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3");
}

:global(.votyijv0m) {
  d: path("M19 9h3");
}

</style>
