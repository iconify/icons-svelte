<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsnj9o-9y"/><path class="xevwjp71u"/><path class="uce-uzwap"/><path class="rr8ohtbyv"/><path class="leef4tbvz"/><path class="jkuojibnm"/><path class="v9qvd19wv"/><path class="wcigoab1j"/><path class="mtax_6bie"/><path class="t3rq50btb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:latency-p99-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.leef4tbvz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mtax_6bie) {
  d: path("M13 16v4");
}

:global(.rr8ohtbyv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

:global(.uce-uzwap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v9qvd19wv) {
  d: path("M5 11v9");
}

:global(.wcigoab1j) {
  d: path("M9 14v6");
}

:global(.xevwjp71u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
