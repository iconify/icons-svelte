<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xi553kbjw"/><path class="pwrx49byc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-pound-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pwrx49byc) {
  d: path("M17 9a4 4 0 1 0-8 0v10m-3 0h12");
}

:global(.xi553kbjw) {
  stroke-opacity: 0.4;
  d: path("M6 14h3m0 0h4");
}

</style>
