<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pzx9fiuzq"/><path class="xr_5e9b5a"/><path class="wqteuxb0p"/><path class="bo9_g-q3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collar-duotone-bold" {...props}></Icon>
<style>
:global(.bo9_g-q3m) {
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pzx9fiuzq) {
  fill: currentColor;
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wqteuxb0p) {
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
}

:global(.xr_5e9b5a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
