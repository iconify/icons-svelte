<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9cahv_vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:connector-add" {...props}></Icon>
<style>
:global(.m9cahv_vb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5v4m5-4v4M4 6.5h12v3a6 6 0 0 1-12 0Zm6 9v6m8-7v7M14.5 18h7");
}

</style>
