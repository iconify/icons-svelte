<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vx4tcy1ux"/><path class="akhe8vn1q"/><path class="x043no3hn"/><path class="s0kxqdbiw"/><path class="l8dn9jbyp"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dune-duotone-regular" {...props}></Icon>
<style>
:global(.akhe8vn1q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.s0kxqdbiw) {
  d: path("M2 15a10 6 0 0 1 20 0");
}

:global(.vx4tcy1ux) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15a10 6 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x043no3hn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
