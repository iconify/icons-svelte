<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jzc5m_ept"/><path class="aw9x48hsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fishing-harbour" {...props}></Icon>
<style>
:global(.aw9x48hsn) {
  d: path("M6.5 12h9L14 15H8Zm5 0V6.5l4 5.5");
}

:global(.jzc5m_ept) {
  d: path("M17.785 5.106a9 9 0 1 1-11.57 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
