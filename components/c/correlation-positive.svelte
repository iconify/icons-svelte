<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxct0l_we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:correlation-positive" {...props}></Icon>
<style>
:global(.sxct0l_we) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17h17M7 17h.01M10 14.5h.01M12.5 12h.01M15 9.5h.01M18 7h.01");
}

</style>
