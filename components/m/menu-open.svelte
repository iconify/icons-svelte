<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk8gosaar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:menu-open" {...props}></Icon>
<style>
:global(.nk8gosaar) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5h11M3.5 12H11m-7.5 5.5h11m6-8.5l-3 3l3 3");
}

</style>
