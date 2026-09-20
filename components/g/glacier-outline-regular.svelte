<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g6e5e7bhp"/><path class="p4c11pbyi"/><path class="ng7_l5bbi"/><path class="qgimpuszh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:glacier-outline-regular" {...props}></Icon>
<style>
:global(.g6e5e7bhp) {
  d: path("m2 8 6 6 6 -6 6 6");
}

:global(.ng7_l5bbi) {
  d: path("m6 4 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p4c11pbyi) {
  d: path("m2 15 6 6 6 -6 6 6");
}

:global(.qgimpuszh) {
  d: path("m14 4 4 4");
}

</style>
