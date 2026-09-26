<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zq7x653mj"/><path class="z14q86kcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z14q86kcr) {
  d: path("M10 21L3.5 21C3.2239 21 3 20.7761 3 20.5L3 14M10 14L3.6 20.4");
}

:global(.zq7x653mj) {
  stroke-opacity: 0.4;
  d: path("M14 3L20.5 3C20.7761 3 21 3.2239 21 3.5L21 10M14 10L20.4 3.6");
}

</style>
