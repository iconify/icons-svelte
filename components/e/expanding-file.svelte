<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ieku9mtxu"/><path class="fdg9awjcp"/><path class="lm96lcbgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expanding-file" {...props}></Icon>
<style>
:global(.fdg9awjcp) {
  d: path("M4 13V8.5h6.5l1-1.5h3l1 1.5H20V13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ieku9mtxu) {
  d: path("M3 21v-8h11l1-1.5h3.5l1 1.5H21v8Z");
}

:global(.lm96lcbgz) {
  d: path("M5 8.5V4h1.5l1-1.5h3l1 1.5H19v4.5");
}

</style>
