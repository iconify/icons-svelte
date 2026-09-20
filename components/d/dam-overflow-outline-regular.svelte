<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="me0af_bhu"/><path class="npv4e-b7s"/><path class="nvnpnwbdj"/><path class="e0ead5bmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dam-overflow-outline-regular" {...props}></Icon>
<style>
:global(.e0ead5bmw) {
  d: path("M3 12h3");
}

:global(.me0af_bhu) {
  d: path("M6 4h4v16H6Z");
}

:global(.npv4e-b7s) {
  d: path("M10 8h4l4 4v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nvnpnwbdj) {
  d: path("M3 8h3");
}

</style>
