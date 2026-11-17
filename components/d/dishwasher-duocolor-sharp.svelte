<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ogq_ynllt"/><path class="odsjhlbmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dishwasher-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.odsjhlbmu) {
  d: path("M4 3h16v18H4Zm0 6h16M8 6h.01M11 6h.01");
}

:global(.ogq_ynllt) {
  stroke-opacity: 0.4;
  d: path("M8 13h8");
}

</style>
