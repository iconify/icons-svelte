<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="osjmvib6z"/><path class="le7pjtb_z"/><path class="iv17tcb7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rabbit-outline-regular" {...props}></Icon>
<style>
:global(.iv17tcb7u) {
  d: path("M14 4.5A1.5 1.5 0 0 1 15.5 3 1.5 1.5 0 0 1 17 4.5v5a1.5 1.5 0 0 1 -1.5 1.5A1.5 1.5 0 0 1 14 9.5Z");
}

:global(.le7pjtb_z) {
  d: path("M7 4.5A1.5 1.5 0 0 1 8.5 3 1.5 1.5 0 0 1 10 4.5v5A1.5 1.5 0 0 1 8.5 11 1.5 1.5 0 0 1 7 9.5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.osjmvib6z) {
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
