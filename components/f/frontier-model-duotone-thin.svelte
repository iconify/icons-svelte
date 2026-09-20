<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtwp3absz"/><path class="jc5wb8hwy"/><path class="h3z-uye4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:frontier-model-duotone-thin" {...props}></Icon>
<style>
:global(.h3z-uye4u) {
  d: path("m8 8 4 -4 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jc5wb8hwy) {
  d: path("m12 11 4 4 -4 4 -4 -4Z");
}

:global(.jtwp3absz) {
  fill: currentColor;
  d: path("m12 11 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
