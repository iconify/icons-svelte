<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hjdjo27qv"/><path class="gfftb7q5s"/><path class="rg1eezbnh"/><path class="j835zw5-z"/><path class="fya2ljx1a"/><path class="ebww8dbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fish-tank-duotone-bold" {...props}></Icon>
<style>
:global(.ebww8dbae) {
  d: path("m9 15 -3 -3");
}

:global(.fya2ljx1a) {
  d: path("M9 15c2 -3 6 -3 8 0 -2 3 -6 3 -8 0");
}

:global(.gfftb7q5s) {
  fill: currentColor;
  d: path("M9 15c2 -3 6 -3 8 0 -2 3 -6 3 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hjdjo27qv) {
  fill: currentColor;
  d: path("M3 6v14h18V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.rg1eezbnh) {
  d: path("M3 6v14h18V6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
