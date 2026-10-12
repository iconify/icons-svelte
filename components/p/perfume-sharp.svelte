<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5xybdj5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:perfume-sharp" {...props}></Icon>
<style>
:global(.j5xybdj5d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 4.25h6.5v3h-6.5zm6.5 1.5h3m-14.5 4h16.5v11.5H3.75zM9 15.5h6");
}

</style>
