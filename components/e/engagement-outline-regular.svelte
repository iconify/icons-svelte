<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrzizubal"/><path class="uu-axlbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:engagement-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nrzizubal) {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.uu-axlbah) {
  d: path("m9 8 3 -3 3 3Z");
}

</style>
