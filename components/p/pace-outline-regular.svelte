<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iqr3ry8kv"/><path class="ym_yrom4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pace-outline-regular" {...props}></Icon>
<style>
:global(.iqr3ry8kv) {
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ym_yrom4f) {
  d: path("M13 2 9 6h3l-4 4");
}

</style>
