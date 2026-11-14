<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nn8vn89fa"/><path class="pielbxb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beatbox" {...props}></Icon>
<style>
:global(.nn8vn89fa) {
  d: path("M2.5 10.5c1.5-2.5 4-3 6-1.5c2-1.5 4.5-1 6 1.5c-1 5-4 6.5-6 6.5s-5-1.5-6-6.5Z");
}

:global(.pielbxb5m) {
  d: path("M5.25 12q3.25 2.5 6.5 0m5.75-4L20 6m-2 6h3m-3.5 4l2.5 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
