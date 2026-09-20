<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vi4joi7cm"/><path class="sxlwlmkmh"/><path class="x67_elb1a"/><path class="wj95cacbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bin-full-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.vi4joi7cm) {
  d: path("M6 12v8h12v-8");
}

:global(.wj95cacbv) {
  d: path("M13 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.x67_elb1a) {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
