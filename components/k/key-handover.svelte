<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8q-hssru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:key-handover" {...props}></Icon>
<style>
:global(.q8q-hssru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7 0H20m-3 0v3m3-3v2.5M4 19h8m-2.5-2.5L12 19l-2.5 2.5");
}

</style>
