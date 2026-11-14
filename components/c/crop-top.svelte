<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8-irzb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crop-top" {...props}></Icon>
<style>
:global(.t8-irzb2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h2.5c0 5.5 7 5.5 7 0H18c0 3.5 1.5 5.5 2 6.5V19H4v-7.5c.5-1 2-3 2-6.5ZM4 16h16");
}

</style>
