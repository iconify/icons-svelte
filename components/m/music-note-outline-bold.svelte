<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-note-outline-bold" {...props}></Icon>
<style>
:global(.ew7y79byi) {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.huj3g_bus) {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nycbsrkgh) {
  d: path("M17 17V5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wwbyt5bkd) {
  d: path("M9 5h8");
}

:global(.xob7qnbfo) {
  d: path("M9 17V5");
}

</style>
