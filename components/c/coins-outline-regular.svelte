<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d9oh1gxrx"/><path class="n32o5nlfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coins-outline-regular" {...props}></Icon>
<style>
:global(.d9oh1gxrx) {
  d: path("M4 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.n32o5nlfd) {
  d: path("M10 11a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
