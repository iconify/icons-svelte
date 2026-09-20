<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mjze8rg7o"/><path class="p7apycb5m"/><path class="endvmnb5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rerank-window-outline-bold" {...props}></Icon>
<style>
:global(.endvmnb5x) {
  d: path("M13.5 15.5H16V21h-2.5");
}

:global(.mjze8rg7o) {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

:global(.p7apycb5m) {
  d: path("M10.5 15.5H8V21h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
