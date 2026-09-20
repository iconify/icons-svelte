<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fnp0mpbza"/><path class="qdo8thqpt"/><path class="xucfzr8ng"/><path class="y0y0ccsoe"/><path class="zy54a7bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-vertical-outline-bold" {...props}></Icon>
<style>
:global(.fnp0mpbza) {
  d: path("m5 9 7 -7 7 7Z");
}

:global(.qdo8thqpt) {
  d: path("m5 15 7 7 7 -7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xucfzr8ng) {
  d: path("M3 12h4");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
