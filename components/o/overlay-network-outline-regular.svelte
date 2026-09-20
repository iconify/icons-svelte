<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pmuiqo95v"/><path class="uxcq0c75d"/><path class="o5h857ycu"/><path class="vq8t-6zzl"/><path class="it83nbbll"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overlay-network-outline-regular" {...props}></Icon>
<style>
:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o5h857ycu) {
  d: path("M17 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.uxcq0c75d) {
  d: path("M5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vq8t-6zzl) {
  d: path("m6 12 6 -6 6 6");
}

</style>
