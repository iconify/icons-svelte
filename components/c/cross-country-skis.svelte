<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2jcpkbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cross-country-skis" {...props}></Icon>
<style>
:global(.l2jcpkbtd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5L15 4q1.5-1.5 3-.5M6 20L18.5 7.5Q20 6 21.5 7");
}

</style>
