<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="o40l0bbgl"/><path class="mo1bh2_2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:consistency-check-outline-regular" {...props}></Icon>
<style>
:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.mo1bh2_2m) {
  d: path("M9 12.5h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o40l0bbgl) {
  d: path("M9 8.5h6");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
