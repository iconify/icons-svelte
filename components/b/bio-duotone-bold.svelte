<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mcqij090l"/><path class="ah3n9l5xk"/><path class="s3lwy2n0b"/><path class="gwl0nvbom"/><path class="efcgw323v"/><path class="l1lmw_bdv"/><path class="x-2ssubtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bio-duotone-bold" {...props}></Icon>
<style>
:global(.ah3n9l5xk) {
  fill: currentColor;
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.efcgw323v) {
  d: path("M5 16a3 3 0 0 1 6 0");
}

:global(.gwl0nvbom) {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l1lmw_bdv) {
  d: path("M13 11h6");
}

:global(.mcqij090l) {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

:global(.s3lwy2n0b) {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.x-2ssubtg) {
  d: path("M13 15h6");
}

</style>
