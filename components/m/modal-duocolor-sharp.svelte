<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yb-073nuj"/><path class="w7mc2oblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:modal-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w7mc2oblu) {
  d: path("M3 4h18v16H3Z");
}

:global(.yb-073nuj) {
  stroke-opacity: 0.4;
  d: path("M7 8h10v8H7Z");
}

</style>
