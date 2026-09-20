<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x5i0m055t"/><path class="bsp8a5bsx"/><path class="emvotkb4z"/><path class="goxocdc6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-external-duotone-regular" {...props}></Icon>
<style>
:global(.bsp8a5bsx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 4h10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.goxocdc6s) {
  d: path("M10 4h10v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x5i0m055t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
