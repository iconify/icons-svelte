<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kryimcc7j"/><path class="j0thbqdzb"/><path class="znn_tgx5z"/><path class="rp--5qbrh"/><path class="khp0b8bxr"/><path class="tk14kvbjb"/><path class="z27xoybfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-glasses-duotone-bold" {...props}></Icon>
<style>
:global(.j0thbqdzb) {
  fill: currentColor;
  d: path("M13 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.khp0b8bxr) {
  d: path("M10.5 13h3");
}

:global(.kryimcc7j) {
  fill: currentColor;
  d: path("M3 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rp--5qbrh) {
  d: path("M13 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tk14kvbjb) {
  d: path("m3 10 2 -2");
}

:global(.z27xoybfi) {
  d: path("m21 10 -2 -2");
}

:global(.znn_tgx5z) {
  d: path("M3 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
