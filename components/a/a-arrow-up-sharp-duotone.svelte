<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qv42ivz-f"/><path class="jrdlzxp_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:a-arrow-up-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jrdlzxp_c) {
  d: path("M19 19V8M22.293 11.2929L19 8L15.707 11.2929");
}

:global(.qv42ivz-f) {
  stroke-opacity: 0.4;
  d: path("M1.93 18.6273L7.002 6L12.074 18.6273M4.19 13H9.813");
}

</style>
