<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw0jptb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bulk-scoop" {...props}></Icon>
<style>
:global(.nw0jptb0h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5h11V12a4.5 4.5 0 0 1-4.5 4.5h-2A4.5 4.5 0 0 1 3 12Zm11 3h7");
}

</style>
