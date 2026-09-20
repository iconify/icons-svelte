<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="it1__ylki"/><path class="kvapwnb7q"/><path class="rcb0dgbps"/><path class="e0qzk-bpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-prompt-list-duotone-bold" {...props}></Icon>
<style>
:global(.e0qzk-bpf) {
  d: path("M19 10h-5l-4 4v6h10v-9");
}

:global(.it1__ylki) {
  fill: currentColor;
  d: path("M16 4h-5L7 8v6h10V5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kvapwnb7q) {
  fill: currentColor;
  d: path("M19 10h-5l-4 4v6h10v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rcb0dgbps) {
  d: path("M16 4h-5L7 8v6h10V5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
