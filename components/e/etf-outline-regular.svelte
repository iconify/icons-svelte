<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vo1-lv2pt"/><path class="oz3eccbug"/><path class="c4khiwgvb"/><path class="iq7hdacem"/><path class="gi1v2vyju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:etf-outline-regular" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.gi1v2vyju) {
  d: path("M13.5 12.5 16 15l-2.5 2.5");
}

:global(.iq7hdacem) {
  d: path("M10.5 12.5 8 15l2.5 2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oz3eccbug) {
  d: path("M7 8a5 5 0 0 1 10 0");
}

:global(.vo1-lv2pt) {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
