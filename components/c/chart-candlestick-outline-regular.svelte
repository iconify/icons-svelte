<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rw52-bbtm"/><path class="f6tip2cru"/><path class="p6nkr755w"/><path class="hq3guo9pr"/><path class="f1p3_92ft"/><path class="hd8_4bbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-candlestick-outline-regular" {...props}></Icon>
<style>
:global(.f1p3_92ft) {
  d: path("M12.5 11a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.f6tip2cru) {
  d: path("M2.5 10a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.hd8_4bbku) {
  d: path("M16 16v3");
}

:global(.hq3guo9pr) {
  d: path("M16 5v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p6nkr755w) {
  d: path("M6 16v4");
}

:global(.rw52-bbtm) {
  d: path("M6 4v4");
}

</style>
