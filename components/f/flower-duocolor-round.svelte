<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ofpokoiuq"/><path class="u1c5eccxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flower-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ofpokoiuq) {
  stroke-opacity: 0.4;
  d: path("M12 9h.01");
}

:global(.u1c5eccxo) {
  d: path("M9 6a3 3 0 0 1 6 0a3 3 0 0 1 0 6a3 3 0 0 1-6 0a3 3 0 0 1 0-6m3 9v6");
}

</style>
