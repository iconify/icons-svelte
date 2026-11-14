<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_nts653d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magnet" {...props}></Icon>
<style>
:global(.t_nts653d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V11a8 8 0 0 1 16 0v10h-5.5V11a2.5 2.5 0 0 0-5 0v10Zm0-4.5h5.5m5 0H20");
}

</style>
