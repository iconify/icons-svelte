<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-i4vhbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lifeguard-tower-public" {...props}></Icon>
<style>
:global(.i-i4vhbjf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8L12 3l8.5 5Zm3 0v4.5h11V8M7 12.5l-2 9m12-9l2 9m-8.5-9v9m3-9v9m-3-5.75h3m-3 3h3");
}

</style>
