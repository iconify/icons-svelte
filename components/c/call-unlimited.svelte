<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqqsxcb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:call-unlimited" {...props}></Icon>
<style>
:global(.qqqsxcb-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21h4l1.5-4.5l-2.5-2C9.25 12 12 9.25 14.5 8l2 2.5L21 9V5a2 2 0 0 0-2-2C10 3 3 10 3 19a2 2 0 0 0 2 2m13-3c-.75-2.5-3.5-2.5-3.5 0s2.75 2.5 3.5 0s3.5-2.5 3.5 0s-2.75 2.5-3.5 0");
}

</style>
