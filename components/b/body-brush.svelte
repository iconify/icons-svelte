<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j76r7rgxu"/><path class="ww0yibbjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:body-brush" {...props}></Icon>
<style>
:global(.j76r7rgxu) {
  d: path("M3.5 9a5.5 4.5 0 1 0 11 0a5.5 4.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ww0yibbjr) {
  d: path("m10.044 13.864l1.945-1.945l6.717 6.717l-1.945 1.945ZM7.5 7.5h.01m2.99 3h.01");
}

</style>
