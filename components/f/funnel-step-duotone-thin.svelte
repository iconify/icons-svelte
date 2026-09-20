<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkxdfrn3s"/><path class="cc0pq4b_o"/><path class="eu82ces9t"/><path class="ozi-k-boi"/><path class="vslz5yb3q"/><path class="kdybz_aht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-step-duotone-thin" {...props}></Icon>
<style>
:global(.cc0pq4b_o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dkxdfrn3s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eu82ces9t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdybz_aht) {
  d: path("M9 17h6");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

</style>
