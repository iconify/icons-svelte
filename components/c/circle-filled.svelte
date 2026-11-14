<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fskgklbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circle-filled" {...props}></Icon>
<style>
:global(.fskgklbds) {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

</style>
