<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwfbrrxqq"/><path class="b-4e0nbmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gallery-duocolor-sharp" {...props}></Icon>
<style>
:global(.b-4e0nbmo) {
  d: path("M3 3h18v14H3Z");
}

:global(.hwfbrrxqq) {
  stroke-opacity: 0.4;
  d: path("m3 13l6-6l5 5l3-3l4 4M3 21h7m4 0h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
