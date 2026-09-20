<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s0epddbdr"/><path class="ggkp0ebth"/><path class="dnor6qp_n"/><path class="f-x5yl3mg"/><path class="vjiab_p7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-assembly-duotone-bold" {...props}></Icon>
<style>
:global(.dnor6qp_n) {
  d: path("M2 8h11");
}

:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.ggkp0ebth) {
  d: path("M13 8a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

:global(.s0epddbdr) {
  fill: currentColor;
  d: path("M13 8a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
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

:global(.vjiab_p7t) {
  d: path("M2 16h11");
}

</style>
