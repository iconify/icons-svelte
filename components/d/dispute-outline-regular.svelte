<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="jlfjgzbqx"/><path class="x1_r36phd"/><path class="z_b_jl_3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dispute-outline-regular" {...props}></Icon>
<style>
:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

:global(.z_b_jl_3m) {
  d: path("m9.5 14 5 -5");
}

</style>
