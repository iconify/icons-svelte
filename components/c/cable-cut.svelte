<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1j1h6bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-cut" {...props}></Icon>
<style>
:global(.t1j1h6bys) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5H10V19H2.5Zm11.5 0h7.5V19H14ZM12 5v4M7 6.5l1.75 3.75M17 6.5l-1.75 3.75");
}

</style>
