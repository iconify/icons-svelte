<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zpm2iyb0f"/><path class="n1oi4j7xe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-to-line-duocolor-sharp" {...props}></Icon>
<style>
:global(.n1oi4j7xe) {
  d: path("m7 18l6-6l-6-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zpm2iyb0f) {
  stroke-opacity: 0.4;
  d: path("M17 6v12");
}

</style>
