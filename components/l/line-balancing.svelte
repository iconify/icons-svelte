<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6_1qjb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:line-balancing" {...props}></Icon>
<style>
:global(.t6_1qjb9x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18m-9 0v9.5m-4 0h8M4 5.5h5.5V11H4Zm10.5 0H20V11h-5.5Z");
}

</style>
