<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d78wq3bxy"/><path class="n-7t0yb1r"/><path class="f5ieidcch"/><path class="q40roytdv"/><path class="a6-q04p3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkout-counter-duotone-regular" {...props}></Icon>
<style>
:global(.a6-q04p3f) {
  d: path("M8.5 5.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2V8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.d78wq3bxy) {
  fill: currentColor;
  d: path("M8.5 5.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2V8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f5ieidcch) {
  d: path("M5 13v8");
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q40roytdv) {
  d: path("M19 13v8");
}

</style>
