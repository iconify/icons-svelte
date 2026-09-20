<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6pqx6b7w"/><path class="rrxso7m3p"/><path class="i49-5fazd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guest-outline-regular" {...props}></Icon>
<style>
:global(.i49-5fazd) {
  d: path("M13 17a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p6pqx6b7w) {
  d: path("M2 3v18h8V3Z");
}

:global(.rrxso7m3p) {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
