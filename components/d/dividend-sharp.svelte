<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="l0r7vlbov"/><circle class="a7q8jib6e"/><circle class="qo9rs7j5k"/><circle class="nlor3-bpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dividend-sharp" {...props}></Icon>
<style>
:global(.a7q8jib6e) {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
}

:global(.l0r7vlbov) {
  cx: 12px;
  cy: 7.25px;
  r: 4.5px;
}

:global(.nlor3-bpa) {
  cx: 17.75px;
  cy: 17.5px;
  r: 3.25px;
}

:global(.qo9rs7j5k) {
  cx: 6.25px;
  cy: 17.5px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
