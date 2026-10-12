<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iurep68ah"/><path class="ij-jo_u4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:checkpoint-save-sharp" {...props}></Icon>
<style>
:global(.ij-jo_u4y) {
  d: path("M6 7v2.75h5M6 21v-4.25h6.5V21M18 7v6.75M18 3h3.25L20 5l1.25 2H18Z");
}

:global(.iurep68ah) {
  d: path("M4.5 6.75h8l1.24 1.24l.77.77L15.75 10v11.25h-13V6.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
