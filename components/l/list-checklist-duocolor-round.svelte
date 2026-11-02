<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="osr_65bii"/><path class="b2_xccbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-checklist-duocolor-round" {...props}></Icon>
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

:global(.osr_65bii) {
  stroke-opacity: 0.4;
  d: path("m3 6l2 2l4-4m-6 8l2 2l4-4m-6 8l2 2l4-4");
}

</style>
