<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_momebyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bowl-empty" {...props}></Icon>
<style>
:global(.v_momebyh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h18c0 5.5-4 9.5-9 9.5s-9-4-9-9.5");
}

</style>
