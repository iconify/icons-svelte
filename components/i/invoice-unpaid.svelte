<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z57jx7vju"/><path class="w-u7zkv4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:invoice-unpaid" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w-u7zkv4i) {
  d: path("M6.5 5.5H13v3H6.5Zm0 6.5H13m-6.5 4h3m8.5-1.5V18m0 3h.01");
}

:global(.z57jx7vju) {
  d: path("M15.2 19.5H3v-17h13.5v9.2");
}

</style>
