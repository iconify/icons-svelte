<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a267w6b7t"/><path class="icl_s5yhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cold-room" {...props}></Icon>
<style>
:global(.a267w6b7t) {
  d: path("M13.2 21.5H2.5v-19H18v9.4");
}

:global(.icl_s5yhb) {
  d: path("M5.5 21.5V6h7v9.7m0 4.6v1.2M9.75 12v3m8.25-.25v6.5m-2.75-4.75l5.5 3m-5.5 0l5.5-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
