<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e51u4gbaa"/><path class="q7yedcbtb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-left-4-duotone" {...props}></Icon>
<style>
:global(.e51u4gbaa) {
  stroke-opacity: 0.4;
  d: path("M3 8L21 8L17 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q7yedcbtb) {
  d: path("M21 16L3 16L7 20");
}

</style>
