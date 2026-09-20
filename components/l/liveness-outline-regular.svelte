<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wxfc8bn6j"/><path class="oa7ibkb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:liveness-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oa7ibkb8p) {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

:global(.wxfc8bn6j) {
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
}

</style>
