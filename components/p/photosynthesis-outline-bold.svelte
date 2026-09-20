<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lbl-xgx4l"/><path class="xbaewdsnx"/><path class="lc7bb5w9b"/><path class="e1_au8jbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:photosynthesis-outline-bold" {...props}></Icon>
<style>
:global(.e1_au8jbg) {
  d: path("m20 9 -3 3");
}

:global(.lbl-xgx4l) {
  d: path("M6 20c0 -9 5.4 -12.6 12.6 -12.6C18.6 14.6 11.4 20 6 20");
}

:global(.lc7bb5w9b) {
  d: path("m20 4 -4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xbaewdsnx) {
  d: path("m16 4 -4 4");
}

</style>
