<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n34rxwehg"/><path class="g86fdm6kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-droplet-sharp-duotone" {...props}></Icon>
<style>
:global(.g86fdm6kx) {
  d: path("M9.8705 10.7535L10.5816 15.4178M13.8248 10.1507L14.5359 14.815");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.n34rxwehg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.4944 7.7692C20.1022 9.4451 21 11.6776 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 11.6776 3.8978 9.4451 5.5056 7.7692L12 1L18.4944 7.7692Z");
  stroke: none;
}

</style>
