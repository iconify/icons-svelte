<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ma3nbxt"/><path class="ra5uied2u"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:matryoshka-outline-regular" {...props}></Icon>
<style>
:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ra5uied2u) {
  d: path("m12 7.5 4.5 4.5 -4.5 4.5L7.5 12Z");
}

:global(.x6ma3nbxt) {
  d: path("m12 3 9 9 -9 9 -9 -9Z");
}

</style>
