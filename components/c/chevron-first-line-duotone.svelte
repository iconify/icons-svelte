<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vgemhwbaj"/><path class="cfxd4se9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-first-line-duotone" {...props}></Icon>
<style>
:global(.cfxd4se9w) {
  d: path("M7.5 5L7.49998 19.0004");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vgemhwbaj) {
  stroke-linejoin: round;
  d: path("M16.5 19L10.5 12L16.5 5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
