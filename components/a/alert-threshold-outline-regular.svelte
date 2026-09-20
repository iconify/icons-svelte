<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="z_-efe0hh"/><path class="z4to5ssqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:alert-threshold-outline-regular" {...props}></Icon>
<style>
:global(.f4yp5uw0u) {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

:global(.k70w93buq) {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z_-efe0hh) {
  d: path("M8.5 9h7");
}

:global(.z4to5ssqg) {
  d: path("m9.5 15 2.5 -2.5 2.5 2.5");
}

</style>
