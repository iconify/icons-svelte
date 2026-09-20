<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="jb_v2ub8s"/><path class="d6pr-0b9u"/><path class="xgrfb-bqu"/><path class="vslz5yb3q"/><path class="x3sflacnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-chart-duotone-bold" {...props}></Icon>
<style>
:global(.d6pr-0b9u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jb_v2ub8s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.khksl7boy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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
