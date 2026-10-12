<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yb-1lsbiy"/><path class="y-kzbdbkl"/><path class="lqzonf2qh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crescent-moon" {...props}></Icon>
<style>
:global(.lqzonf2qh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.5Q5.8 11.7 8 12q-2.2.3-2.5 2.5Q5.2 12.3 3 12q2.2-.3 2.5-2.5");
}

:global(.y-kzbdbkl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 9h.01m-.76 6h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yb-1lsbiy) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.25a9.25 9.25 0 1 1 0 17.5a10.08 10.08 0 0 0 0-17.5");
}

</style>
