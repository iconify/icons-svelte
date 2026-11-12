<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vnl89fbsd"/><path class="h4f8xqbrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:page-margins-duocolor-sharp" {...props}></Icon>
<style>
:global(.h4f8xqbrj) {
  d: path("M5 3h14v18H5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vnl89fbsd) {
  stroke-opacity: 0.4;
  d: path("M9 7h6v10H9Z");
}

</style>
