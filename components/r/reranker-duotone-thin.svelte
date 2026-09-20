<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xodoppbub"/><path class="r-_xorlci"/><path class="ixx7a8jxa"/><path class="sooj-ebve"/><path class="hgb637bhu"/><path class="x2rmxpb0x"/><path class="bv72su-ri"/><path class="autc-bc3p"/><path class="bvirm9d4j"/><path class="a2pxmcc-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reranker-duotone-thin" {...props}></Icon>
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

:global(.hgb637bhu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 16 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixx7a8jxa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r-_xorlci) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sooj-ebve) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2rmxpb0x) {
  d: path("M3 6h13");
}

:global(.xodoppbub) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
