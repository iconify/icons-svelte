<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viyc7_lkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dirham-sign" {...props}></Icon>
<style>
:global(.viyc7_lkk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v16h4c4.5 0 7.5-3.25 7.5-8s-3-8-7.5-8Zm-3 6.25h16m-16 3.5h16");
}

</style>
