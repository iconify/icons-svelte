<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr2-ivrbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bed-x" {...props}></Icon>
<style>
:global(.nr2-ivrbg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v15m0-7h18m0-3.5V12m-5.5 3.5l5 5m0-5l-5 5");
}

</style>
