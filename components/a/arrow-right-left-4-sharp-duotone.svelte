<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k_yf0ckfx"/><path class="qgmjcmbvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-left-4-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k_yf0ckfx) {
  stroke-opacity: 0.4;
  d: path("M2 8L21 8L16.7071 3.7071");
}

:global(.qgmjcmbvp) {
  d: path("M22 16L3 16L7.2929 20.2929");
}

</style>
