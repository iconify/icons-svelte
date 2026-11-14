<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u_nmsbcje"/><path class="zq-lwyuor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chinchilla" {...props}></Icon>
<style>
:global(.u_nmsbcje) {
  d: path("M3.5 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zq-lwyuor) {
  d: path("M4.25 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16.25 18C20.5 19.5 22 15 20 12.5m-7.5 0h.01");
}

</style>
