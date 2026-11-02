<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v80rx_bgt"/><path class="ycx3-jb_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:egg-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.v80rx_bgt) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3c3.5 0 7 5.5 7 11a7 7 0 1 1-14 0C5 8.5 8.5 3 12 3");
}

:global(.ycx3-jb_k) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3C8.5 3 5 8.5 5 14a7 7 0 0 0 14 0c0-5.5-3.5-11-7-11m3 11a3 3 0 0 1-3 3");
}

</style>
