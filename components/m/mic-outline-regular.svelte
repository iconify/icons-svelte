<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o0c886b7j"/><path class="fmxp6_bjo"/><path class="xyf3o9drf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mic-outline-regular" {...props}></Icon>
<style>
:global(.fmxp6_bjo) {
  d: path("M17 10a5 5 0 0 1 -10 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o0c886b7j) {
  d: path("M9 5a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

:global(.xyf3o9drf) {
  d: path("M12 15v5");
}

</style>
