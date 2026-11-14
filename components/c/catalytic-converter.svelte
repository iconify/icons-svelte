<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1w4o-1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:catalytic-converter" {...props}></Icon>
<style>
:global(.rc1w4o-1k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6.5h2a5.5 5.5 0 0 1 5.5 5.5a5.5 5.5 0 0 1-5.5 5.5h-2A5.5 5.5 0 0 1 5.5 12A5.5 5.5 0 0 1 11 6.5M2.5 12h3m13 0h3m-19-2.5v5m19-5v5");
}

</style>
