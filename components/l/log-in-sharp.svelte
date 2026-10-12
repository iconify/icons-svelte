<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sex6nfb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:log-in-sharp" {...props}></Icon>
<style>
:global(.sex6nfb-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 3.75h5.5v16.5h-5.5M3.75 12h10.5M10.5 8.25L14.25 12l-3.75 3.75");
}

</style>
