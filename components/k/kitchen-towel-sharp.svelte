<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbu577b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kitchen-towel-sharp" {...props}></Icon>
<style>
:global(.nbu577b1p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.25h18.5m-15 0h11.5v17H6.25zm0 5.25h11.5m-11.5 6.25h11.5m-11.5 2.5h11.5");
}

</style>
