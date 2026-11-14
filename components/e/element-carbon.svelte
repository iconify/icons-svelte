<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t5sx8fx7s"/><path class="uag740b4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-carbon" {...props}></Icon>
<style>
:global(.t5sx8fx7s) {
  d: path("M7 3.5h10L21.5 9L12 20.5L2.5 9ZM2.5 9h19");
}

:global(.uag740b4g) {
  d: path("M9.5 3.5L8 9l4 11.5m2.5-17L16 9l-4 11.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
