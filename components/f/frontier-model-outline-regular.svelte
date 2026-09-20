<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jc5wb8hwy"/><path class="h3z-uye4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:frontier-model-outline-regular" {...props}></Icon>
<style>
:global(.h3z-uye4u) {
  d: path("m8 8 4 -4 4 4");
}

:global(.jc5wb8hwy) {
  d: path("m12 11 4 4 -4 4 -4 -4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
