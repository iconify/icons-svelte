<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kj2g1tcln"/><path class="ugt-67b9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chiropractic" {...props}></Icon>
<style>
:global(.kj2g1tcln) {
  d: path("M5 2.5h6.5V6H5Zm1.25 5h6.5V11h-6.5Zm-.5 5h6.5V16h-6.5Zm-1.25 5H11V21H4.5Zm7-13.25l1.75.75m-.5 4.25l1.75.75m-2.25 4.25L14 15m-3 4.25l1.75.75M17.5 4.5c3.25 3.5 3.25 10.5 0 14");
}

:global(.ugt-67b9k) {
  d: path("M17.5 15.75v2.75h2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
