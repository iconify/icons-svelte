<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qdtl06k3j"/><path class="vbpqdmten"/><path class="wjj8_yb8n"/><path class="xj_u41y2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-left-duotone-bold" {...props}></Icon>
<style>
:global(.qdtl06k3j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vbpqdmten) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wjj8_yb8n) {
  d: path("m11 4 -8 8 8 8");
}

:global(.xj_u41y2v) {
  d: path("m20 4 -8 8 8 8");
}

</style>
