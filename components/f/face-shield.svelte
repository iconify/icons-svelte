<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g7_-2rb4f"/><path class="s3cn8o35s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:face-shield" {...props}></Icon>
<style>
:global(.g7_-2rb4f) {
  d: path("M7 21.5V18c-2-1.5-2.75-3.5-2.75-5.75c0-3.75 2.75-6.5 6.25-6.5s6 2.25 6 5.75l1.25 3q.375.75-.75.75h-.5v2c0 1-.75 1.75-1.75 1.75H13v2.5");
}

:global(.s3cn8o35s) {
  d: path("M13 3c5.5.75 8.5 5 8.5 9.5c0 3.5-1.5 6.25-3.75 7.75M5.75 6.5L13 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
