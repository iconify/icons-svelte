<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd0hnxbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:classified-ads" {...props}></Icon>
<style>
:global(.gd0hnxbno) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9v10a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 3 19V9h3V3.5h14.5V18a2.5 2.5 0 0 1-2.5 2.5H4.5M9 7.5h8.5M9 12h3m2.75 0h2.75M9 16.5h3m2.75 0h2.75");
}

</style>
