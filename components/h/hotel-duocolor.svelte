<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ru57a09hd"/><path class="kzfe-7bfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hotel-duocolor" {...props}></Icon>
<style>
:global(.kzfe-7bfh) {
  d: path("M3 21h18M5 21V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16M8 7h.01M8 11h.01M12 7h.01M12 11h.01M16 7h.01M16 11h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ru57a09hd) {
  stroke-opacity: 0.4;
  d: path("M9 16h6m-5 5v-5m4 5v-5");
}

</style>
