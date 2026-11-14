<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j92ihdcdt"/><path class="ewv59-bdc"/><path class="ilix7lbhg"/><path class="i7udc-b9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:garden-bucket" {...props}></Icon>
<style>
:global(.ewv59-bdc) {
  d: path("m5 10l1.75 9c0 1.25 2.25 2.25 5.25 2.25s5.25-1 5.25-2.25L19 10");
}

:global(.i7udc-b9p) {
  d: path("M6 15.5c2 1.5 10 1.5 12 0");
}

:global(.ilix7lbhg) {
  d: path("M12 17a7 7 0 0 1 0-14");
}

:global(.j92ihdcdt) {
  d: path("M5 10a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
