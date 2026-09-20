<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="odu85s2ca"/><path class="lzc28-gln"/><path class="yzcdzmlnf"/><path class="t6wf8ob_n"/><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:library-duotone-thin" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lzc28-gln) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.odu85s2ca) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 12 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t6wf8ob_n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.woetzacvo) {
  d: path("m4 12 8 -8 8 8");
}

:global(.yzcdzmlnf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
