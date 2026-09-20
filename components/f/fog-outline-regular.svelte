<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="vzfmp7bra"/><path class="ys-dg812g"/><path class="wneoubc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fog-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vzfmp7bra) {
  d: path("M5 11h14");
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
