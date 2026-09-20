<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdmxjh-cj"/><path class="rnz95vbcp"/><path class="fb8er8b7t"/><path class="o8od38cnm"/><path class="dp_v0obrq"/><path class="yazo7scbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:breakfast-included-duotone-thin" {...props}></Icon>
<style>
:global(.dp_v0obrq) {
  d: path("M8 3v3");
}

:global(.fb8er8b7t) {
  d: path("M14 9a2.5 2.5 0 0 1 0 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdmxjh-cj) {
  fill: currentColor;
  d: path("M6 8v7h8V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.rnz95vbcp) {
  d: path("M6 8v7h8V8Z");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
