<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c95x86p7n"/><path class="zc5m_3bog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pixel-heart" {...props}></Icon>
<style>
:global(.c95x86p7n) {
  d: path("M6 3h4.5v3h3V3H18v3h3v6h-3v3h-3v3h-1.5v3h-3v-3H9v-3H6v-3H3V6h3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zc5m_3bog) {
  d: path("M6 9V6h3");
}

</style>
