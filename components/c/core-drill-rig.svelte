<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfx5qxpwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:core-drill-rig" {...props}></Icon>
<style>
:global(.pfx5qxpwl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M6.75 21L12 2.5L17.25 21m-8-8.75h5.5M12 2.5V21");
}

</style>
