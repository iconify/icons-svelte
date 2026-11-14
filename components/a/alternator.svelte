<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qb4qkj-nv"/><path class="bmm9uobmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:alternator" {...props}></Icon>
<style>
:global(.bmm9uobmc) {
  d: path("m9.75 10.5l-2.25 4h3l-2.25 3");
}

:global(.qb4qkj-nv) {
  d: path("M2.5 14a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0ZM16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.25 11.75l6-10.5M6.5 8l11-4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
