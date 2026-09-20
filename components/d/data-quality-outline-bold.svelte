<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nrqy16b7j"/><path class="x22av82oi"/><path class="pvfbz5b4i"/><path class="o50_pabww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-quality-outline-bold" {...props}></Icon>
<style>
:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.o50_pabww) {
  d: path("m16 12 2 2 4 -4");
}

:global(.pvfbz5b4i) {
  d: path("M3 18h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

</style>
