<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s60_lqkqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-lira" {...props}></Icon>
<style>
:global(.s60_lqkqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5v16c4.75 0 8.5-3 8.5-8M6 11l7-3m-7 7l7-3");
}

</style>
