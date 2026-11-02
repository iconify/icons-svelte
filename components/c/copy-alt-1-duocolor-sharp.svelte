<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwbv977cx"/><path class="n70g8xb1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-1-duocolor-sharp" {...props}></Icon>
<style>
:global(.n70g8xb1k) {
  d: path("M3 9h12v12H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zwbv977cx) {
  stroke-opacity: 0.4;
  d: path("M9 9V3h12v12h-6");
}

</style>
