<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ktl0q7bve"/><path class="nw8-8vb0d"/><path class="jlt4pubuu"/><path class="iedujiqkb"/><path class="fotxf46ll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exactly-once-duotone-bold" {...props}></Icon>
<style>
:global(.fotxf46ll) {
  d: path("m14 12.5 3 3 4.5 -4.5");
}

:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jlt4pubuu) {
  d: path("M4 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.ktl0q7bve) {
  fill: currentColor;
  d: path("M4 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nw8-8vb0d) {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

</style>
