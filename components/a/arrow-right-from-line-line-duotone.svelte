<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8cf4vb5m"/><path class="qwnb2m7yv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-from-line-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m8cf4vb5m) {
  d: path("M3 4L3 20");
}

:global(.qwnb2m7yv) {
  d: path("M8 12L21 12M16.625 8L21 12L16.625 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
