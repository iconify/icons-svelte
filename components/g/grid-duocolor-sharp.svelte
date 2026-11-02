<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tota1lyqq"/><path class="k6s87vboi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:grid-duocolor-sharp" {...props}></Icon>
<style>
:global(.k6s87vboi) {
  d: path("M4 4h6v6H4Zm0 10h6v6H4Zm10 0h6v6h-6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tota1lyqq) {
  stroke-opacity: 0.4;
  d: path("M14 4h6v6h-6Z");
}

</style>
