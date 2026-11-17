<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ei8fqnb-b"/><path class="um5xk4bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:oven-duocolor-sharp" {...props}></Icon>
<style>
:global(.ei8fqnb-b) {
  stroke-opacity: 0.4;
  d: path("M8 13h8v5H8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.um5xk4bzf) {
  d: path("M4 3h16v18H4Zm4 3h.01M12 6h.01M16 6h.01M8 10h8");
}

</style>
