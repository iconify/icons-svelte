<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o8te6lb4v"/><path class="xtv8je8bw"/><path class="nq1z19bud"/><path class="amdyfrbnw"/><path class="djifetbcn"/><path class="x2rmxpb0x"/><path class="bv72su-ri"/><path class="autc-bc3p"/><path class="bvirm9d4j"/><path class="a2pxmcc-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reranker-duotone-regular" {...props}></Icon>
<style>
:global(.a2pxmcc-f) {
  d: path("m18 16 2 2 2 -2");
}

:global(.amdyfrbnw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.djifetbcn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 16 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nq1z19bud) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8te6lb4v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2rmxpb0x) {
  d: path("M3 6h13");
}

:global(.xtv8je8bw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
