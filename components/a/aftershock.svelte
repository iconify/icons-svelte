<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zigs-27wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aftershock" {...props}></Icon>
<style>
:global(.zigs-27wa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H5m0 0l2-9l2.5 18l2-13l2 8l2-6l2 4l2-2h2");
}

</style>
