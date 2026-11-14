<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb379xbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:edge-computing" {...props}></Icon>
<style>
:global(.gb379xbsb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15H10a2.5 2.5 0 0 0 0-5a3.25 3.25 0 0 0-6 .5A2.25 2.25 0 0 0 5.75 15M17.125 4.5h1.75A2.625 2.625 0 0 1 21.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-1.75a2.625 2.625 0 0 1-2.625-2.625v-9.75A2.625 2.625 0 0 1 17.125 4.5m-2.625 5h7m-7 5h7m-9-2.5h2");
}

</style>
