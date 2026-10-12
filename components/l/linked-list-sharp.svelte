<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sef63e_ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:linked-list-sharp" {...props}></Icon>
<style>
:global(.sef63e_ey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h7.5v6.5h-7.5zm11 10h7.5v6.5h-7.5zM10.25 7h7.25v5.25m-2-2l2 2l2-2M13.75 17h-4.5m0-2.25v4.5");
}

</style>
