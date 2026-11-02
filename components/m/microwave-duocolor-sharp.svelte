<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fc3ud-bge"/><path class="phakvlbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microwave-duocolor-sharp" {...props}></Icon>
<style>
:global(.fc3ud-bge) {
  stroke-opacity: 0.4;
  d: path("M7 8h6v6H7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phakvlbgq) {
  d: path("M3 4h18v14H3Zm4 14v2m10-2v2m0-12v6");
}

</style>
