<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gdyzmbc6q"/><path class="nt_q6sb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:car-speeding" {...props}></Icon>
<style>
:global(.gdyzmbc6q) {
  d: path("M9.5 15.5H8V12l2.5-1.5L13 7h4.5l2.5 3.5l1.5.75v4.25h-1m-7 0h3");
}

:global(.nt_q6sb4u) {
  d: path("M9.5 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 9H7m-4.5 3H5m-2.5 3H5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
