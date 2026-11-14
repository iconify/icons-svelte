<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt-ovz7ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bass-clef" {...props}></Icon>
<style>
:global(.xt-ovz7ou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8.5a5 5 0 0 1 10 0c0 7-4.5 11-10.5 13m.5-13h.01m13.99-2h.01m-.01 6h.01");
}

</style>
