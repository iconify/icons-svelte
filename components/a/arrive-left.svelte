<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ofrwl5b8s"/><path class="ykapxmb2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrive-left" {...props}></Icon>
<style>
:global(.ofrwl5b8s) {
  d: path("M12 21.5c-3-3-6.5-7-6.5-12a6.5 6.5 0 0 1 13 0c0 5-3.5 9-6.5 12Zm-3-12h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ykapxmb2h) {
  d: path("M11.5 7L9 9.5l2.5 2.5");
}

</style>
