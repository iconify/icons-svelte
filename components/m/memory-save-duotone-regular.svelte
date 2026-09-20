<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v7k_gnx8j"/><path class="povs9wlph"/><path class="arlddp6_a"/><path class="q4yaf_b-b"/><path class="xw66a0v9s"/><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-save-duotone-regular" {...props}></Icon>
<style>
:global(.arlddp6_a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.czv374byt) {
  d: path("M10 16h11");
}

:global(.gzf8q_b5i) {
  d: path("m5 9 2 2 -2 2");
}

:global(.i33dqh0th) {
  d: path("M10 11h11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.povs9wlph) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 9 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pv9xj1b7g) {
  d: path("M2 11h5");
}

:global(.q4yaf_b-b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v7k_gnx8j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7gyblbnl) {
  d: path("M10 6h11");
}

:global(.xw66a0v9s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
