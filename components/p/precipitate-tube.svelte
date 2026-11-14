<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnaqtgb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:precipitate-tube" {...props}></Icon>
<style>
:global(.tnaqtgb2a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10M8.5 3v14.5a3.5 3.5 0 0 0 7 0V3m-7 6.5h7m-7 5h7M12 18h.01");
}

</style>
