<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:library-outline-thin" {...props}></Icon>
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

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.woetzacvo) {
  d: path("m4 12 8 -8 8 8");
}

</style>
