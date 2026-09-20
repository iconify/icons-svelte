<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwufvfb8q"/><path class="wlp3ibbib"/><path class="lg-3ttj_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:garage-outline-regular" {...props}></Icon>
<style>
:global(.hwufvfb8q) {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

:global(.lg-3ttj_m) {
  d: path("M6 16.5h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

</style>
