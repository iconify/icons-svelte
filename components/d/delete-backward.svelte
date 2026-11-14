<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp_3rsblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delete-backward" {...props}></Icon>
<style>
:global(.rp_3rsblf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5h10.5A2.5 2.5 0 0 1 21 7.5v9a2.5 2.5 0 0 1-2.5 2.5H8l-5.5-7Zm4 4.5l5 5m0-5l-5 5");
}

</style>
