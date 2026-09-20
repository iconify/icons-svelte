<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nx55f6tub"/><path class="ugv0mtd4a"/><path class="st2_lbcfm"/><path class="dbfzjzb3n"/><path class="atfn67x6m"/><path class="f_vuvgsaw"/><path class="bj2hlhbfp"/><path class="ecph9tq5i"/><path class="t3rq50btb"/><path class="fdua8zbmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backpressure-duotone-regular" {...props}></Icon>
<style>
:global(.atfn67x6m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.dbfzjzb3n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ecph9tq5i) {
  d: path("M3 18h12");
}

:global(.f_vuvgsaw) {
  d: path("M3 6h12");
}

:global(.fdua8zbmm) {
  d: path("m16 7 3 -3 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nx55f6tub) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.st2_lbcfm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

:global(.ugv0mtd4a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
