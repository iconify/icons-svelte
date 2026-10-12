<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnx_v7bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rainwater-tank-sharp" {...props}></Icon>
<style>
:global(.cnx_v7bnx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 2.75l1.35 1.747v.753a1.35 1.35 0 0 1-2.7 0v-.753zm-7.25 5.5h5m-2.5 0v2.5m-7 0h14v10.5h-14zM8 14.25v4.25m10.25.25h3");
}

</style>
