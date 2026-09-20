<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xfo-vjbcz"/><path class="if5ft31dv"/><path class="ssjs9weax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-alarm-outline-regular" {...props}></Icon>
<style>
:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ssjs9weax) {
  d: path("M19 8c2 2 2 6 0 8");
}

:global(.xfo-vjbcz) {
  d: path("M6 17c2 -2 2 -5 2 -7 0 -3 2 -5 4 -5s4 2 4 5c0 2 0 5 2 7Z");
}

</style>
