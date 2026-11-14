<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h5ffsbcbr"/><path class="yji2l03lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:price-tag-euro" {...props}></Icon>
<style>
:global(.h5ffsbcbr) {
  d: path("M8.5 4.5h11v15h-11l-5-7.5ZM8.25 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yji2l03lf) {
  d: path("M16.5 9.5a3.25 3.25 0 1 0 0 5m-5.75-3.25h4m-4 1.5h4");
}

</style>
