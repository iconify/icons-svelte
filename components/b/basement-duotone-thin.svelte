<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzbhhg_xy"/><path class="vl001wbav"/><path class="jttv79b0k"/><path class="atoje4bsc"/><path class="e2r0vmbrh"/><path class="kpiqhd6nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:basement-duotone-thin" {...props}></Icon>
<style>
:global(.atoje4bsc) {
  d: path("M2 6h20");
}

:global(.e2r0vmbrh) {
  d: path("M4 6v5h5v4h5v4h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jttv79b0k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 18.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kpiqhd6nn) {
  d: path("M20 18.5V21");
}

:global(.rzbhhg_xy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vl001wbav) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v5h5v4h5v4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
