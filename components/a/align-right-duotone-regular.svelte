<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="dj18udbqn"/><path class="c89h0bq8c"/><path class="xgrfb-bqu"/><path class="tee3b-ble"/><path class="kp3vwzbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-right-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c89h0bq8c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dj18udbqn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kp3vwzbyx) {
  d: path("M6 18h15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tee3b-ble) {
  d: path("M10 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
