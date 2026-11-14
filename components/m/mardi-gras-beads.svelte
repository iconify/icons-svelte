<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6sp_nbyn"/><path class="k8k7f8-xq"/><path class="rtxm9ebkq"/><path class="qibzr6_4w"/><path class="ybdb7lb2p"/><path class="rlu2y3zpg"/><path class="qdih00bug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mardi-gras-beads" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k8k7f8-xq) {
  d: path("M7 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.qdih00bug) {
  d: path("M18 7a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 18 7");
}

:global(.qibzr6_4w) {
  d: path("M2.5 7A1.75 1.75 0 1 0 6 7a1.75 1.75 0 1 0-3.5 0m11 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.rlu2y3zpg) {
  d: path("M17.5 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.rtxm9ebkq) {
  d: path("M4.5 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.t6sp_nbyn) {
  d: path("M10.25 17.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.ybdb7lb2p) {
  d: path("M16 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
