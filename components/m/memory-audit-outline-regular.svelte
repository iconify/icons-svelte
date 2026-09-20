<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="jotdonbiv"/><path class="a-p6m2b3f"/><path class="ux6apgnet"/><path class="aes764-qd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-audit-outline-regular" {...props}></Icon>
<style>
:global(.a-p6m2b3f) {
  d: path("M10.5 6H16");
}

:global(.aes764-qd) {
  d: path("M10.5 10H16");
}

:global(.jotdonbiv) {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ux6apgnet) {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
