<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ujwj70gna"/><path class="vjij4k2la"/><path class="g2i9ptb4h"/><path class="sxlwlmkmh"/><path class="j_lyr1ori"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-v-duotone-bold" {...props}></Icon>
<style>
:global(.g2i9ptb4h) {
  d: path("m6 3 6 6 6 -6Z");
}

:global(.j_lyr1ori) {
  d: path("m6 21 6 -6 6 6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.ujwj70gna) {
  fill: currentColor;
  d: path("m6 3 6 6 6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vjij4k2la) {
  fill: currentColor;
  d: path("m6 21 6 -6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
