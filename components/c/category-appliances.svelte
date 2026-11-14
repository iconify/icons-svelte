<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="klpny775a"/><path class="uxpb_bbre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-appliances" {...props}></Icon>
<style>
:global(.klpny775a) {
  d: path("M5 2.5h14v19H5Zm0 6h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uxpb_bbre) {
  d: path("M9 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM8 5.5h.01");
}

</style>
