<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4-u5fbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:capacitor-bank" {...props}></Icon>
<style>
:global(.f4-u5fbzd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5v14m4-14v14M2.5 12H10m4 0h7.5");
}

</style>
