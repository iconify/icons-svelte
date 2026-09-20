<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jrpnc2pnl"/><path class="xedmbxbzm"/><path class="bfi7-obrv"/><path class="taxmbub4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delivery-map-outline-regular" {...props}></Icon>
<style>
:global(.bfi7-obrv) {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

:global(.jrpnc2pnl) {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.xedmbxbzm) {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
