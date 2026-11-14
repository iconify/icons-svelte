<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc6d5nb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:first-aid-sign" {...props}></Icon>
<style>
:global(.vc6d5nb6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8h7a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-6.5A3.5 3.5 0 0 1 8 8M2.5 2.5v3m0-1.5H20M7.5 4v4m8-4v4m-4 3v7.5m-3.75-3.75h7.5");
}

</style>
