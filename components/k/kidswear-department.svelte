<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztz-2sblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kidswear-department" {...props}></Icon>
<style>
:global(.ztz-2sblm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11l1 10.5h-5L12 17l-1.5 4.5h-5Zm2-5.5h7V11h-7Zm0 0L7 2.5m8.5 3l1.5-3m-6.5 5.75h3");
}

</style>
