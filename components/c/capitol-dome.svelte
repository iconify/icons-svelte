<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gng3c1b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:capitol-dome" {...props}></Icon>
<style>
:global(.gng3c1b5s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 15.5a7.5 7.5 0 0 1 15 0ZM12 3v5m0 3v4.5M3 19h18");
}

</style>
