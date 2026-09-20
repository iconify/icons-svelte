<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v3mivhbeb"/><path class="pcl5pkbcw"/><path class="votyijv0m"/><path class="tlwdv3zao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baking-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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
