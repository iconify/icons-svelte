<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tj8-r-bnr"/><path class="c_o5l5o1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handbag-duotone-sharp" {...props}></Icon>
<style>
:global(.c_o5l5o1s) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8h14l2 12H3zm3 0a4 4 0 1 1 8 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.tj8-r-bnr) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m19 8l2 12H3L5 8Z");
}

</style>
