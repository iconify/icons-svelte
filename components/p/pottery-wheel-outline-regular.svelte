<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hya5w9myb"/><path class="ys-dg812g"/><path class="fmlaifbpn"/><path class="qdn88l2uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pottery-wheel-outline-regular" {...props}></Icon>
<style>
:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.hya5w9myb) {
  d: path("M9 13c-2 -2 -1 -5 1 -7h4c2 2 3 5 1 7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
