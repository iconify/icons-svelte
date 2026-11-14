<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0om4vbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leave-now" {...props}></Icon>
<style>
:global(.a0om4vbdu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m5 5v9m-2.5 0h5m4-3h6M19 16l2.5 2.5L19 21");
}

</style>
