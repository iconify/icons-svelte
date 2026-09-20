<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="qvytntb8g"/><path class="s13ysjbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocr-outline-thin" {...props}></Icon>
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

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qvytntb8g) {
  d: path("M7 10h10");
}

:global(.s13ysjbyf) {
  d: path("M7 14h7");
}

:global(.xt7079b9x) {
  d: path("M16 20h5v-4");
}

</style>
