<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="leef4tbvz"/><path class="ofc1f3max"/><path class="tcoeiw6rn"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="aeqgdde5a"/><path class="pd0q9ub5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cross-join-duotone-thin" {...props}></Icon>
<style>
:global(.aeqgdde5a) {
  d: path("m7 6 10 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.leef4tbvz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrmo-yb4e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ofc1f3max) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 6 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pd0q9ub5m) {
  d: path("M17 6 7 16");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

:global(.tcoeiw6rn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6 7 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
