<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq2xexblz"/><path class="osqky4cvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-backfill" {...props}></Icon>
<style>
:global(.oq2xexblz) {
  d: path("M20.5 6.5H4m3-3l-3 3l3 3M2.5 13H7v4.5H2.5Zm7.25 0h4.5v4.5h-4.5ZM17 13h4.5v4.5H17Z");
}

:global(.osqky4cvz) {
  fill: currentColor;
  d: path("M3.5 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm7.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
