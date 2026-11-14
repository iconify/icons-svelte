<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft74snbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:courthouse-check" {...props}></Icon>
<style>
:global(.ft74snbbn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8L12 3l9.5 5Zm0 11.5h9.9m8.8 0h.3M6 11v5m4-5v5m4-5v4.3m4-4.3v3.8M14.75 18l2 2L21 15.75");
}

</style>
