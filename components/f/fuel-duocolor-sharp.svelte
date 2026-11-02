<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_hd4bg-f"/><path class="r-892qiye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fuel-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r-892qiye) {
  d: path("M3 3h10v18H3Zm0 6h10");
}

:global(.w_hd4bg-f) {
  stroke-opacity: 0.4;
  d: path("M13 12h4v5h4V7l-3-3");
}

</style>
