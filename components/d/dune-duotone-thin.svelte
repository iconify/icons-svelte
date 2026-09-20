<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th5tk2b6w"/><path class="uzkjx1-8e"/><path class="evcx__bzi"/><path class="s0kxqdbiw"/><path class="l8dn9jbyp"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dune-duotone-thin" {...props}></Icon>
<style>
:global(.evcx__bzi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.s0kxqdbiw) {
  d: path("M2 15a10 6 0 0 1 20 0");
}

:global(.th5tk2b6w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15a10 6 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uzkjx1-8e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
