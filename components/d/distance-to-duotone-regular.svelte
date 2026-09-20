<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fli2w14co"/><path class="tczno9b3c"/><path class="bq0_6ubvh"/><path class="bsqy413qs"/><path class="ils7yp4cg"/><path class="yhzmxzc3v"/><path class="f77ctdb-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distance-to-duotone-regular" {...props}></Icon>
<style>
:global(.bq0_6ubvh) {
  d: path("M2 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.bsqy413qs) {
  d: path("M16 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.f77ctdb-m) {
  d: path("M21 13.5v5");
}

:global(.fli2w14co) {
  fill: currentColor;
  d: path("M2 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tczno9b3c) {
  fill: currentColor;
  d: path("M16 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yhzmxzc3v) {
  d: path("M3 13.5v5");
}

</style>
