<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlb9y5byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frame-tablet" {...props}></Icon>
<style>
:global(.hlb9y5byf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.5h10.5a3.5 3.5 0 0 1 3.5 3.5v12a3.5 3.5 0 0 1-3.5 3.5H6.75a3.5 3.5 0 0 1-3.5-3.5V6a3.5 3.5 0 0 1 3.5-3.5M12 18.25h.01");
}

</style>
