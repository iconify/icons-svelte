<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="s6vpnyndj"/><path class="maqjne6ar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-arrow-right-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.maqjne6ar) {
  d: path("M13 20H2V7M2 7V4H22V7M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M22 7V11M15 17H22M18.707 20.293L22 17L18.707 13.707");
}

:global(.s6vpnyndj) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4H19C20.657 4 22 5.343 22 7L12.707 11C12.285 11.282 11.715 11.282 11.293 11L2 7C2 5.343 3.343 4 5 4Z");
  stroke: none;
}

</style>
