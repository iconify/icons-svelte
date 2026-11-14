<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4a-_ktdj"/><path class="qr4lo0b_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ice-screw" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p4a-_ktdj) {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.qr4lo0b_p) {
  d: path("M11.5 8.5h1A1.5 1.5 0 0 1 14 10v10a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 20V10a1.5 1.5 0 0 1 1.5-1.5m-4 5l9-2m-9 6l9-2");
}

</style>
