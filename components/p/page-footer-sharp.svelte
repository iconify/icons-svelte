<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0q1rbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:page-footer-sharp" {...props}></Icon>
<style>
:global(.kg0q1rbsu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 16.5h16.5v4.75H3.75zm0-2.25V2.75h16.5v11.5M7.5 7h9m-9 3.5h6");
}

</style>
