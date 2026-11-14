<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r28b_tbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cursor-crosshair" {...props}></Icon>
<style>
:global(.r28b_tbrk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6m0 7v6M2.5 12h6m7 0h6M12 12h.01");
}

</style>
