<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aopsj6wlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pint-glass" {...props}></Icon>
<style>
:global(.aopsj6wlf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h11l-.25 2.5q.75 1.5 0 3L16 21H8L6.75 8.5q-.75-1.5 0-3Z");
}

</style>
