<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdes4n-zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boat-hook" {...props}></Icon>
<style>
:global(.tdes4n-zg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 21.75l13-13a3.536 3.536 0 1 0-5 0M5.75 18.5l2.5 2.5");
}

</style>
