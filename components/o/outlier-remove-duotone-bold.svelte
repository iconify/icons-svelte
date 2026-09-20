<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvz2lnbll"/><path class="f3oxrjbrz"/><path class="o7k-2fb3i"/><path class="yc9k_xbzo"/><path class="wqtdbh_2x"/><path class="j7chpbkqv"/><path class="keqc2pbxm"/><path class="xcjkf-bzr"/><path class="n4avueb2x"/><path class="yzgjkacew"/><path class="szv640b_x"/><path class="v79lu9btt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:outlier-remove-duotone-bold" {...props}></Icon>
<style>
:global(.f3oxrjbrz) {
  fill: currentColor;
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j7chpbkqv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20.5 9.5 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.keqc2pbxm) {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n4avueb2x) {
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.o7k-2fb3i) {
  fill: currentColor;
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rvz2lnbll) {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.szv640b_x) {
  d: path("m16.5 9.5 4 4");
}

:global(.v79lu9btt) {
  d: path("m20.5 9.5 -4 4");
}

:global(.wqtdbh_2x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16.5 9.5 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xcjkf-bzr) {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yc9k_xbzo) {
  fill: currentColor;
  d: path("M16.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yzgjkacew) {
  d: path("M16.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
