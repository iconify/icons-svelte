<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o72p0hsyz"/><path class="v7xfanbfw"/><path class="d8gf8fboh"/><path class="nt94z-wbn"/><path class="zo05kh48x"/><path class="vqk_j23jd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keypoint-outline-bold" {...props}></Icon>
<style>
:global(.d8gf8fboh) {
  d: path("M7.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nt94z-wbn) {
  d: path("M14.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.o72p0hsyz) {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v7xfanbfw) {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vqk_j23jd) {
  d: path("M13 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zo05kh48x) {
  d: path("M9 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
