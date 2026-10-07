<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wn473ibit"/><path class="d_bw9tbze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-filter-duotone" {...props}></Icon>
<style>
:global(.d_bw9tbze) {
  d: path("M6 12L18 12M10 18L14 18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wn473ibit) {
  stroke-opacity: 0.4;
  d: path("M2 6L22 6");
}

</style>
