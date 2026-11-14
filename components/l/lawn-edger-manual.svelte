<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnd3ju1cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lawn-edger-manual" {...props}></Icon>
<style>
:global(.lnd3ju1cf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5a6.5 6.5 0 0 0 13 0Zm6.5 0V3M9 3h6");
}

</style>
