<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnzvalwps"/><path class="ua11a9d-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caps-lock-duocolor-sharp" {...props}></Icon>
<style>
:global(.fnzvalwps) {
  stroke-opacity: 0.4;
  d: path("M9 21h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ua11a9d-z) {
  d: path("M12 17H9v-6H4l8-8l8 8h-5v6z");
}

</style>
