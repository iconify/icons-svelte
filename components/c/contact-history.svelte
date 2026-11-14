<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t6giiwb8s"/><path class="o4cma47ad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contact-history" {...props}></Icon>
<style>
:global(.o4cma47ad) {
  d: path("M5.25 2.25v3h3M6.5 7.5h11v9h-11Zm3 3h5m-5 3h3");
}

:global(.t6giiwb8s) {
  d: path("M2.5 12a9.5 9.5 0 1 0 2.75-6.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
