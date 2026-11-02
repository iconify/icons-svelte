<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mlo5-tbia"/><path class="xef6vnl4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-open-duocolor-sharp" {...props}></Icon>
<style>
:global(.mlo5-tbia) {
  stroke-opacity: 0.4;
  d: path("m13 15l3-3l-3-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xef6vnl4d) {
  d: path("M4 4h16v16H4Zm5 0v16");
}

</style>
