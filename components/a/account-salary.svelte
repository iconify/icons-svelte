<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r82yjackc"/><path class="pcl9wg7bq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-salary" {...props}></Icon>
<style>
:global(.pcl9wg7bq) {
  d: path("M9.75 7.25a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0ZM2.5 12l9.5 5l9.5-5");
}

:global(.r82yjackc) {
  d: path("M2.5 10h19v11.5h-19ZM4 10V5.5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
