<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r3bxhz_dv"/><path class="pnlccdbpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-check-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pnlccdbpc) {
  d: path("M9.8055 12.5771L11.5778 14.4L14.1924 10.1214");
}

:global(.r3bxhz_dv) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 20L18 20C20.6233 20 23 17.6233 23 15C23 12.6937 21.163 10.578 18.9365 10.1004C18.4644 6.7612 15.4245 4 12 4C8.5755 4 5.5356 6.7612 5.0635 10.1004C2.837 10.578 1 12.6937 1 15C1 17.6233 3.3767 20 6 20Z");
  stroke: none;
}

</style>
