<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_7l4cbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:premium-breakdown" {...props}></Icon>
<style>
:global(.f_7l4cbwx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m9.5 0V2.5m0 9.5l8 4.75");
}

</style>
