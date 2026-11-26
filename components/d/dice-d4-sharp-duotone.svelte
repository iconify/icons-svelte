<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pvr0zy2jy"/><path class="gx_rsjonv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-d4-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.gx_rsjonv) {
  d: path("M12 3.0001L2.002 21L21.998 21Z");
}

:global(.pvr0zy2jy) {
  stroke-opacity: 0.4;
  d: path("M12 3L12 14M3.0104 19.1834L12 14L20.9896 19.1834");
}

</style>
