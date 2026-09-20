<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jutdvybnj"/><path class="wumf77bxt"/><path class="wi71wvbqq"/><path class="bg56fj76r"/><path class="a6z1jcjqs"/><path class="ivqg9reic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cell-arch-outline-regular" {...props}></Icon>
<style>
:global(.a6z1jcjqs) {
  d: path("M8 16a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.bg56fj76r) {
  d: path("M16.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ivqg9reic) {
  d: path("M11 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jutdvybnj) {
  d: path("M2.5 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wi71wvbqq) {
  d: path("M13.5 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.wumf77bxt) {
  d: path("M5.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
