<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="ciwf6fbqv"/><path class="ri_favbdz"/><path class="hmmm1s-ek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-vad-outline-thin" {...props}></Icon>
<style>
:global(.ciwf6fbqv) {
  d: path("M5.5 10.5h3");
}

:global(.hmmm1s-ek) {
  d: path("M15.5 10.5h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.ri_favbdz) {
  d: path("M9.5 12.5 12 10l2.5 2.5");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
