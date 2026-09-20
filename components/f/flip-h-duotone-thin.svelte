<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zajsl6b4z"/><path class="u6i63ebjk"/><path class="bc38ssbmv"/><path class="r7xk8o29f"/><path class="nxg78fr6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-h-duotone-thin" {...props}></Icon>
<style>
:global(.bc38ssbmv) {
  d: path("m3 6 6 6 -6 6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nxg78fr6n) {
  d: path("m21 6 -6 6 6 6Z");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.u6i63ebjk) {
  fill: currentColor;
  d: path("m21 6 -6 6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zajsl6b4z) {
  fill: currentColor;
  d: path("m3 6 6 6 -6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
