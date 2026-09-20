<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ttpxlcc5b"/><path class="wfmdw-bov"/><path class="m3ubefbgj"/><path class="z55just5o"/><path class="qjx5s3xna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingress-k8s-outline-bold" {...props}></Icon>
<style>
:global(.m3ubefbgj) {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.qjx5s3xna) {
  d: path("M15 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ttpxlcc5b) {
  d: path("M12 3v3.5");
}

:global(.wfmdw-bov) {
  d: path("M9.5 4 12 6.5 14.5 4");
}

:global(.z55just5o) {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
