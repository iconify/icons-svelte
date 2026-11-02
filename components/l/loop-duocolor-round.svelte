<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fst13_7nd"/><path class="yebf7bbwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:loop-duocolor-round" {...props}></Icon>
<style>
:global(.fst13_7nd) {
  stroke-opacity: 0.4;
  d: path("m8 21l3-3l-3-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yebf7bbwe) {
  d: path("M15 18h2a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h4");
}

</style>
