<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nq6h01f_i"/><path class="coh3tkbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:external-link-alt-duotone-sharp" {...props}></Icon>
<style>
:global(.coh3tkbov) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 19h5V5H5v5m-1 5h5v5m0-5l-6 6");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.nq6h01f_i) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 19V5h14v14Z");
}

</style>
