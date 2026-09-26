<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="aus8vg1ze"/><path class="oup9fib8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-commit-horizontal-sharp-fill" {...props}></Icon>
<style>
:global(.aus8vg1ze) {
  d: path("M2 12L10 12M14 12L22 12");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oup9fib8n) {
  fill: currentColor;
  d: path("M12 8C14.0711 8 16 9.9289 16 12C16 14.0711 14.0711 16 12 16C9.9289 16 8 14.0711 8 12C8 9.9289 9.9289 8 12 8Z");
  stroke: none;
}

</style>
