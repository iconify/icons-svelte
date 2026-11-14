<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boj7hcc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heading-3" {...props}></Icon>
<style>
:global(.boj7hcc6q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5v14m8-14v14m-8-7h8m4.25-1.75C16.25 9.5 17 9 18 9c1.25 0 2.25.75 2.25 2.25s-1 2.5-2.75 2.5c2 0 3 1 3 2.5C20.5 18 19.25 19 17.75 19c-1 0-1.75-.5-2.25-1.25");
}

</style>
