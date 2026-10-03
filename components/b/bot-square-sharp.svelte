<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="lvsowdyvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-square-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.lvsowdyvi) {
  d: path("M11.8705 6.7535L12.5816 11.4178M15.8248 6.1507L16.5359 10.815");
}

:global(.x-_5ilohg) {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>
