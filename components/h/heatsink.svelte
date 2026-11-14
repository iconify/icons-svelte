<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiaztm33m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heatsink" {...props}></Icon>
<style>
:global(.oiaztm33m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 15h10.75A2.625 2.625 0 0 1 20 17.625v.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 17.875v-.25A2.625 2.625 0 0 1 6.625 15M6.5 4v11M10 4v11m4-11v11m3.5-11v11");
}

</style>
