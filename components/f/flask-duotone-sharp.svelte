<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="auwowsroz"/><path class="jr02fp_yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flask-duotone-sharp" {...props}></Icon>
<style>
:global(.auwowsroz) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 15l3 6H4l3-6Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jr02fp_yr) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3v6L4 21h16L14 9V3M8 3h8M7 15h10");
}

</style>
