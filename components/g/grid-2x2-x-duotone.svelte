<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vvsigaftl"/><path class="ehk9n8qxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-x-duotone" {...props}></Icon>
<style>
:global(.ehk9n8qxo) {
  d: path("M16 16L22 22M22 16L16 22");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vvsigaftl) {
  stroke-opacity: 0.4;
  d: path("M2 11L18 11C19.1046 11 20 10.1046 20 9L20 5C20 3.3431 18.6569 2 17 2L5 2C3.3431 2 2 3.3431 2 5L2 17C2 18.6569 3.3431 20 5 20L9 20C10.1046 20 11 19.1046 11 18L11 2");
}

</style>
