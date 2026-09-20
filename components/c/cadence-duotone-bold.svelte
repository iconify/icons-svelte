<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yfuyijbwt"/><path class="pc9haabcx"/><path class="erreycbys"/><path class="syzpzeigb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cadence-duotone-bold" {...props}></Icon>
<style>
:global(.erreycbys) {
  d: path("m12 13 5 -5");
}

:global(.pc9haabcx) {
  d: path("M5 13a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.syzpzeigb) {
  d: path("m15 4 5 5");
}

:global(.yfuyijbwt) {
  fill: currentColor;
  d: path("M5 13a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
