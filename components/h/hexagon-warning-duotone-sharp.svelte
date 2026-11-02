<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bnv35hhxa"/><path class="msrioybri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-warning-duotone-sharp" {...props}></Icon>
<style>
:global(.bnv35hhxa) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 12v5l-8 4l-8-4V7l8-4l8 4Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.msrioybri) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12v5l-8 4l-8-4V7l8-4l8 4zm-8-3v4m0 3h.01");
}

</style>
