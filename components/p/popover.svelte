<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t17uaacjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:popover" {...props}></Icon>
<style>
:global(.t17uaacjx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7H9l3-3.5L15 7h4.5a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2m2 4.25h11m-11 4.5h7");
}

</style>
