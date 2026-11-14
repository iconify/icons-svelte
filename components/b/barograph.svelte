<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="par-1lbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barograph" {...props}></Icon>
<style>
:global(.par-1lbnf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m2.75-6.75L7 7m5-4.5V5m6.75.25L17 7m-5 5l2.25-3.75M12 12h.01");
}

</style>
