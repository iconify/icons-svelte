<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="bk5n09bgv"/><path class="va0vmebdx"/><path class="xgrfb-bqu"/><path class="vslz5yb3q"/><path class="x3sflacnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-chart-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bk5n09bgv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.va0vmebdx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.x3sflacnk) {
  d: path("M9 18h6");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
