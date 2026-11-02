<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ywxhrbdhn"/><path class="r21jxhxfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:aspect-ratio-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r21jxhxfq) {
  d: path("M3 5h18v14H3Z");
}

:global(.ywxhrbdhn) {
  stroke-opacity: 0.4;
  d: path("M7 12V9h3m7 3v3h-3");
}

</style>
