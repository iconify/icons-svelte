<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jw8scnbdr"/><path class="pb4s0mydj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:factory-duocolor-round" {...props}></Icon>
<style>
:global(.jw8scnbdr) {
  stroke-opacity: 0.4;
  d: path("M8 16h.01M12 16h.01M16 16h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pb4s0mydj) {
  d: path("M3 21h18M5 21V5a2 2 0 1 1 4 0v7l5-3v3l5-3v12");
}

</style>
