<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3xbxdblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:profile-add-account" {...props}></Icon>
<style>
:global(.g3xbxdblk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M3 20.5c0-3.75 3-6 7-6c1.632 0 2.931.333 4.033.863M18 15v6m-3-3h6");
}

</style>
