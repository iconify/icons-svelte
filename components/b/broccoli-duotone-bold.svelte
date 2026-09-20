<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s9ivncb1z"/><path class="t2xnbczjm"/><path class="lkivjibuo"/><path class="p6px4qbbr"/><path class="pmv9af26x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:broccoli-duotone-bold" {...props}></Icon>
<style>
:global(.lkivjibuo) {
  d: path("M12 13v7");
}

:global(.p6px4qbbr) {
  d: path("M12 16H8");
}

:global(.pmv9af26x) {
  d: path("M12 16h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s9ivncb1z) {
  fill: currentColor;
  d: path("M5 13a4 4 0 0 1 4 -6 4 4 0 0 1 6 0 4 4 0 0 1 4 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t2xnbczjm) {
  d: path("M5 13a4 4 0 0 1 4 -6 4 4 0 0 1 6 0 4 4 0 0 1 4 6Z");
}

</style>
