<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaluqebmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pudding-sharp" {...props}></Icon>
<style>
:global(.zaluqebmc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.75H16l.3 1.21l2.15 8.83l.3 1.21H5.25l.3-1.21L7.7 7.96L8 6.75zM6.6 10.5h10.8M3 21h18");
}

</style>
