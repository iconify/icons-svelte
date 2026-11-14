<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j-e1gk-hd"/><path class="sb1gxdskl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-tag" {...props}></Icon>
<style>
:global(.j-e1gk-hd) {
  d: path("M11.677 19.115L9 18l-6 2.5V6l6-2.5L15 6l6-2.5v9.6M9 3.5V18m6-12v5.7");
}

:global(.sb1gxdskl) {
  d: path("M14.5 14.5h4L22 18l-3.5 3.5h-4ZM17 18h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
