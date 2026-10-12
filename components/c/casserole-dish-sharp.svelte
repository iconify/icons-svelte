<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiij-fb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:casserole-dish-sharp" {...props}></Icon>
<style>
:global(.iiij-fb1n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.5h6.25v-2h3v2h6.25m-14.5 3h13.5v6H5.25zm0 0h-2.5m16 0h2.5");
}

</style>
