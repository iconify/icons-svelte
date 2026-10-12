<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d2ni52jkt"/><path class="olicmnbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-down-up-duotone" {...props}></Icon>
<style>
:global(.d2ni52jkt) {
  stroke-opacity: 0.4;
  d: path("M7 4L12 9L17 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olicmnbwb) {
  d: path("M7 20L12 15L17 20");
}

</style>
