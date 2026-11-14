<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izu2u5bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:awareness-ribbon-double" {...props}></Icon>
<style>
:global(.izu2u5bob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5L13.5 9c1.5-2 1-6.5-2.5-6.5S7 7 8.5 9l4.934 6.676M18 15v6m-3-3h6");
}

</style>
