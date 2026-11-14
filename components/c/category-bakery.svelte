<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xzz91fbeq"/><path class="mjye9w2ln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-bakery" {...props}></Icon>
<style>
:global(.mjye9w2ln) {
  d: path("M7.75 6q0 4 1.25 6.75M16.25 6q0 4-1.25 6.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xzz91fbeq) {
  d: path("M3.5 19.5C1 13 5.5 4.5 12 4.5s11 8.5 8.5 15c-2-5-5-7-8.5-7s-6.5 2-8.5 7Z");
}

</style>
