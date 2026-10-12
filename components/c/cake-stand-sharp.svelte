<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlikcms7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cake-stand-sharp" {...props}></Icon>
<style>
:global(.mlikcms7y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25h12.5v8H5.75zm0 3.25h12.5m-15.5 4.75h18.5m-9.25 0v8m-3.75 0h7.5");
}

</style>
