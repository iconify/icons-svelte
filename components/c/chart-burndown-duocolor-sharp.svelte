<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-x1nwbug"/><path class="fducfywsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-burndown-duocolor-sharp" {...props}></Icon>
<style>
:global(.fducfywsi) {
  d: path("M7 7h4l3 5h3l4 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-x1nwbug) {
  stroke-opacity: 0.4;
  d: path("M3 4v16h18");
}

</style>
