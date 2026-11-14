<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kut8z3b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frequency-table" {...props}></Icon>
<style>
:global(.kut8z3b-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5v15m4-15v15m4-15v15m4-15v15m-15.5-3l19-9");
}

</style>
