<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6guzjh7r"/><path class="j8arz0w3t"/><path class="f8gsx7b5s"/><path class="l0v-b4kbr"/><path class="hclo6jb2r"/><path class="ltl8_ccdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-purifier-duotone-bold" {...props}></Icon>
<style>
:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.j8arz0w3t) {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.ltl8_ccdr) {
  d: path("M3 6h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x6guzjh7r) {
  fill: currentColor;
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
