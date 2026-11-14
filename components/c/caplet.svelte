<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxivecxxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caplet" {...props}></Icon>
<style>
:global(.zxivecxxk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.929 7.757l2.828-2.828a3.5 3.5 0 0 1 4.95 0l6.364 6.364a3.5 3.5 0 0 1 0 4.95l-2.828 2.828a3.5 3.5 0 0 1-4.95 0l-6.364-6.364a3.5 3.5 0 0 1 0-4.95m3.182 8.132l7.778-7.778");
}

</style>
