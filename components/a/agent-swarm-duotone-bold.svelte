<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ydkocbbew"/><path class="ltmp_ybuy"/><path class="g3g-jmb4g"/><path class="sm0j5q50b"/><path class="ru3t32xqk"/><path class="h7k_twb0c"/><path class="jt9_y_e3f"/><path class="d_0vbfv0w"/><path class="ad0-p6dru"/><path class="wylvx_bde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-swarm-duotone-bold" {...props}></Icon>
<style>
:global(.ad0-p6dru) {
  d: path("M12.27 10.28a3 3 0 1 1 -2.54 0");
}

:global(.d_0vbfv0w) {
  d: path("M20.27 11.28a3 3 0 1 1 -2.54 0");
}

:global(.g3g-jmb4g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20.27 11.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.jt9_y_e3f) {
  d: path("M17.27 2.28a3 3 0 1 1 -2.54 0");
}

:global(.ltmp_ybuy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.27 2.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ru3t32xqk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.27 16.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sm0j5q50b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.27 10.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wylvx_bde) {
  d: path("M8.27 16.28a3 3 0 1 1 -2.54 0");
}

:global(.ydkocbbew) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
