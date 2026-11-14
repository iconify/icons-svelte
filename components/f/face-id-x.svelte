<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_jeduzvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:face-id-x" {...props}></Icon>
<style>
:global(.e_jeduzvz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2M8 20.5H6A2.5 2.5 0 0 1 3.5 18v-2M9 8.5h.01m5.99 0h.01M12 8.5V12h-1m-1.5 2.25c1.25 1.25 3.75 1.25 5 0m2 2.25l4 4m0-4l-4 4");
}

</style>
