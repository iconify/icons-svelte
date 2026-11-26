<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbp9zjbwl"/><path class="s-ck0tdyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-filter-x-two-tone" {...props}></Icon>
<style>
:global(.fbp9zjbwl) {
  stroke-opacity: 0.4;
  d: path("M2 7H14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s-ck0tdyz) {
  d: path("M6 13H18M10 19H14M18 5L22 9M22 5L18 9");
}

</style>
