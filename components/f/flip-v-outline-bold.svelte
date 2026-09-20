<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g2i9ptb4h"/><path class="sxlwlmkmh"/><path class="j_lyr1ori"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-v-outline-bold" {...props}></Icon>
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

</style>
