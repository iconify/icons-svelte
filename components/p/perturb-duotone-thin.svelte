<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkxdfrn3s"/><path class="pto756llr"/><path class="ozi-k-boi"/><path class="ph2id7bdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:perturb-duotone-thin" {...props}></Icon>
<style>
:global(.dkxdfrn3s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.ph2id7bdf) {
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.pto756llr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
