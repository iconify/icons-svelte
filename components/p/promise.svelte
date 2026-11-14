<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="su3vw8bra"/><path class="j1t34yoiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:promise" {...props}></Icon>
<style>
:global(.j1t34yoiz) {
  d: path("M15 2.5v5h5M9 11.75A2.5 2.5 0 1 1 12.5 14c-.75.5-1 1-1 1.75m0 2.75h.01");
}

:global(.su3vw8bra) {
  d: path("M4 2.5h11l5 5v14H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
