<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tsevlt2dd"/><path class="wj4ljftik"/><path class="jtmtyidol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:butter-outline-regular" {...props}></Icon>
<style>
:global(.jtmtyidol) {
  d: path("M3 16h18c0 3 -4 5 -9 5s-9 -2 -9 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tsevlt2dd) {
  d: path("M6 7v6h12V7Z");
}

:global(.wj4ljftik) {
  d: path("M10 7v6");
}

</style>
