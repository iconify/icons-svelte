<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zyu_ccbvv"/><path class="fv2g8ea_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-sharp-fill" {...props}></Icon>
<style>
:global(.fv2g8ea_c) {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 9L21 9");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zyu_ccbvv) {
  fill: currentColor;
  d: path("M3 3L21 3L21 9L3 9L3 3Z");
  stroke: none;
}

</style>
