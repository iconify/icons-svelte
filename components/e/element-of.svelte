<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qad3s1jjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:element-of" {...props}></Icon>
<style>
:global(.qad3s1jjo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 5.5H12a6.5 6.5 0 0 0 0 13h6.5M5.5 12h13");
}

</style>
