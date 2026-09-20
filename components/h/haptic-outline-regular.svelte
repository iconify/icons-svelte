<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oayjtvtuh"/><path class="yxwimoiqt"/><path class="klj1k5byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:haptic-outline-regular" {...props}></Icon>
<style>
:global(.klj1k5byh) {
  d: path("M4.17 14.83a4 4 0 0 1 0 -5.66");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oayjtvtuh) {
  d: path("M8 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.yxwimoiqt) {
  d: path("M19.83 9.17a4 4 0 0 1 0 5.66");
}

</style>
