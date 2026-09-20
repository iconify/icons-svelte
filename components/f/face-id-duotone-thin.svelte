<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gf0hswvuq"/><path class="pfjq2-b9j"/><path class="e9bhdvbgs"/><path class="ja9qpyb-y"/><path class="xmcykibok"/><path class="rc-__xbag"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:face-id-duotone-thin" {...props}></Icon>
<style>
:global(.a-r3j5f7z) {
  d: path("M3 16v4h5");
}

:global(.a71lhwniq) {
  d: path("M16 4h5v4");
}

:global(.dxxnlbcax) {
  d: path("M3 8V4h5");
}

:global(.dy-bj6bwq) {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.e9bhdvbgs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gf0hswvuq) {
  fill: currentColor;
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja9qpyb-y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pfjq2-b9j) {
  fill: currentColor;
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rc-__xbag) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xmcykibok) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xt7079b9x) {
  d: path("M16 20h5v-4");
}

</style>
