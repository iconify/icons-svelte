<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f-qcku-wb"/><path class="y9s618baa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-left-2-sharp-duotone" {...props}></Icon>
<style>
:global(.f-qcku-wb) {
  stroke-opacity: 0.4;
  d: path("M7 4.5L22 4.5M7 9.5L22 9.5M7 14.5L19 14.5M7 19.5L15 19.5");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y9s618baa) {
  d: path("M3 2L3 22");
}

</style>
