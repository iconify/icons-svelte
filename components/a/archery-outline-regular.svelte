<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ndk47rb8x"/><path class="wuvisubmw"/><path class="em798y7rn"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:archery-outline-regular" {...props}></Icon>
<style>
:global(.em798y7rn) {
  d: path("M6 12h14");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.ndk47rb8x) {
  d: path("M8 3c6 3 6 15 0 18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

</style>
