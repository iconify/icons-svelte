<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="csg0wlbjc"/><path class="i66aruydi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:length-limit-sign" {...props}></Icon>
<style>
:global(.csg0wlbjc) {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0ZM5.5 9.5v5m13-5v5M7.25 12h9.5");
}

:global(.i66aruydi) {
  d: path("M9.5 9.75L7.25 12l2.25 2.25m5-4.5L16.75 12l-2.25 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
