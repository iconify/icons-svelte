<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="e9pwlacgz"/><path class="gi6lp8bso"/><path class="ssv44kbxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:key-pair" {...props}></Icon>
<style>
:global(.e9pwlacgz) {
  cx: 8px;
  cy: 16px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.gi6lp8bso) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16h.01");
}

:global(.ssv44kbxz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 12.25l8.5-8.5m-3 3L19.5 9m-4.75.25L16.5 11");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
