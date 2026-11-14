<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gpgsg_dlq"/><path class="r17dtnssx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:champagne-toast" {...props}></Icon>
<style>
:global(.gpgsg_dlq) {
  d: path("m8.075 6.386l4.366 1.089l-2.542 7.096l-2.911-.726ZM4.324 20.395l4.852 1.21L6.75 21l1.693-6.792");
}

:global(.r17dtnssx) {
  d: path("m11.559 7.475l4.366-1.089l1.087 7.459l-2.911.726Zm3.265 14.13l4.852-1.21L17.25 21l-1.693-6.792M10 2.75h.01M14 2.5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
