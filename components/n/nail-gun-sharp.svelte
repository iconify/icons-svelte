<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yozrxy_ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nail-gun-sharp" {...props}></Icon>
<style>
:global(.yozrxy_ri) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.75h16.75v5h-3l1.25 8.5h-4l-1.25-8.5H7.5v3.75H3.25V4.75zM3.75 16.5h3m-1.5 0v4.75");
}

</style>
