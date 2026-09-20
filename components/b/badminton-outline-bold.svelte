<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="icjnx2bvb"/><path class="jl-a685iy"/><path class="di0j27ojs"/><path class="hqu8-q-5e"/><path class="mwf5pf3ps"/><path class="vn2a6xb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:badminton-outline-bold" {...props}></Icon>
<style>
:global(.di0j27ojs) {
  d: path("M17 16c2 -4 3 -9 4 -13");
}

:global(.hqu8-q-5e) {
  d: path("M3 3h18");
}

:global(.icjnx2bvb) {
  d: path("M12 20c-3 0 -5 -2 -5 -4h10c0 2 -2 4 -5 4");
}

:global(.jl-a685iy) {
  d: path("M7 16C5 12 4 7 3 3");
}

:global(.mwf5pf3ps) {
  d: path("M9 4v11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vn2a6xb1r) {
  d: path("M15 4v11");
}

</style>
