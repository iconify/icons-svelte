<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uxz1l1b3s"/><path class="g-x4tgpdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:popover-duocolor-sharp" {...props}></Icon>
<style>
:global(.g-x4tgpdu) {
  d: path("M3 7h6l3-4l3 4h6v14H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uxz1l1b3s) {
  stroke-opacity: 0.4;
  d: path("M7 12h10M7 16h6");
}

</style>
