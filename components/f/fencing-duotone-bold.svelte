<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ndosv0bel"/><path class="v4_esibhq"/><path class="kzztgab9v"/><path class="pqgwswb7d"/><path class="ywch90sba"/><path class="uwi1_aczt"/><path class="u1gt5absq"/><path class="r0uia_bgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fencing-duotone-bold" {...props}></Icon>
<style>
:global(.kzztgab9v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 4 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ndosv0bel) {
  fill: currentColor;
  d: path("M3 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pqgwswb7d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4 5 20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r0uia_bgu) {
  d: path("M19 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u1gt5absq) {
  d: path("M3 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uwi1_aczt) {
  d: path("M21 4 5 20");
}

:global(.v4_esibhq) {
  fill: currentColor;
  d: path("M19 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ywch90sba) {
  d: path("m3 4 16 16");
}

</style>
