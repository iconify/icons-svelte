<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjkrkcega"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:national-anthem" {...props}></Icon>
<style>
:global(.pjkrkcega) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5v19m0-18q3.75-2 7.5 0t7.5 0V11q-.906.483-1.812.733m-.967.2Q14.361 12.259 12 11q-3.75-2-7.5 0m9.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0v-5m0 0l2.75 1");
}

</style>
