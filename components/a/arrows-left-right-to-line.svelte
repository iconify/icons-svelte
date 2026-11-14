<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf0ye-bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrows-left-right-to-line" {...props}></Icon>
<style>
:global(.qf0ye-bbj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h6.25M5.5 9l3.25 3l-3.25 3m16-3h-6.25m3.25-3l-3.25 3l3.25 3M12 4v16");
}

</style>
