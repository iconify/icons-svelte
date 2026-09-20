<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tv5rv9b5z"/><path class="k187sabpz"/><path class="kpavcn10r"/><path class="o70nty8gv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:allergen-duotone-bold" {...props}></Icon>
<style>
:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.kpavcn10r) {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

:global(.o70nty8gv) {
  d: path("m12 2 7 7H5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tv5rv9b5z) {
  fill: currentColor;
  d: path("m12 2 7 7H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
