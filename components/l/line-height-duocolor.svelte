<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o8i27cbmn"/><path class="b2_xccbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:line-height-duocolor" {...props}></Icon>
<style>
:global(.b2_xccbks) {
  d: path("M13 6h8m-8 6h8m-8 6h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8i27cbmn) {
  stroke-opacity: 0.4;
  d: path("M6 4v16M9 7L6 4L3 7m0 10l3 3l3-3");
}

</style>
