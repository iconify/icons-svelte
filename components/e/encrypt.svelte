<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw1acp8hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:encrypt" {...props}></Icon>
<style>
:global(.xw1acp8hq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h4a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-2.5A3.5 3.5 0 0 1 6 11m-.75 0V8.5a2.75 2.75 0 0 1 5.5 0V11m4.75 4.75h6m-2.25-2.25l2.25 2.25L19.25 18");
}

</style>
