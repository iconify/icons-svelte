<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="bjkhv3eln"/><path class="afx8cdcbt"/><path class="qe97cg-lx"/><path class="dqeovmbtl"/><path class="fua3x2iyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:growth-chart-duotone-bold" {...props}></Icon>
<style>
:global(.afx8cdcbt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 6h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bjkhv3eln) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 18 4 -4 3 3 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dqeovmbtl) {
  d: path("m5 18 4 -4 3 3 7 -7");
}

:global(.fua3x2iyd) {
  d: path("M17 6h4");
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yxjvqtiry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
