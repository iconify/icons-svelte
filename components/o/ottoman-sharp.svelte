<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkh5c8b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ottoman-sharp" {...props}></Icon>
<style>
:global(.mkh5c8b4a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.25h16.5v4.5H3.75zm1.5 4.5h13.5v8.5H5.25zm2.5 8.5v2m8.5-2v2");
}

</style>
