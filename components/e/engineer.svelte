<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js52l1b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:engineer" {...props}></Icon>
<style>
:global(.js52l1b4i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.5h2a5 5 0 0 1 10 0h2Zm3.5 0V10a3.5 3.5 0 0 0 7 0V8.5m-11 12c0-2.5 3.25-4.25 7.5-4.25s7.5 1.75 7.5 4.25");
}

</style>
