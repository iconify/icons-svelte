<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x2rmxpb0x"/><path class="bv72su-ri"/><path class="autc-bc3p"/><path class="bvirm9d4j"/><path class="a2pxmcc-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reranker-outline-bold" {...props}></Icon>
<style>
:global(.a2pxmcc-f) {
  d: path("m18 16 2 2 2 -2");
}

:global(.autc-bc3p) {
  d: path("M3 18h13");
}

:global(.bv72su-ri) {
  d: path("M3 12h13");
}

:global(.bvirm9d4j) {
  d: path("M20 6v12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x2rmxpb0x) {
  d: path("M3 6h13");
}

</style>
