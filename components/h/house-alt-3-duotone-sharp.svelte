<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xczztcmgz"/><path class="dz89iccgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-3-duotone-sharp" {...props}></Icon>
<style>
:global(.dz89iccgx) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 11l9-8l9 8m-2-1.778V21H5V9.222");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.xczztcmgz) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 3l9 8l-.013.015L19 9.249V21H5V9.249l-1.987 1.766L3 11Z");
}

</style>
