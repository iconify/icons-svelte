<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="g37o2ccdt"/><path class="rfw129v8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:contactless-pay-outline-regular" {...props}></Icon>
<style>
:global(.g37o2ccdt) {
  d: path("M10.12 15.32a2 2 0 0 1 3.76 0");
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.rfw129v8m) {
  d: path("M8.24 14.63a4 4 0 0 1 7.5 0");
}

</style>
