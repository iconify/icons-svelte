<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnz58g38j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:potted-plant" {...props}></Icon>
<style>
:global(.wnz58g38j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.741 14.5h8.518a1.75 1.75 0 0 1 1.697 2.174l-.875 3.5a1.75 1.75 0 0 1-1.697 1.326H8.616a1.75 1.75 0 0 1-1.697-1.326l-.875-3.5A1.75 1.75 0 0 1 7.741 14.5m4.259 0V9m0 1.5c-4.5 0-7-2.5-7-7c4.5 0 7 2.5 7 7M12 9c4 0 7-2.25 7-6c-4 0-7 2.25-7 6");
}

</style>
