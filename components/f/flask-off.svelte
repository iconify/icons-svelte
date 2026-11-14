<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0n_4jb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flask-off" {...props}></Icon>
<style>
:global(.x0n_4jb-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5v2.6m-1.723 6.174L5 18.5q-1 2 1.25 2h10.331m-1.352-9.165L14 9V3.5m-5.5 0h7m-12 0l17 17");
}

</style>
