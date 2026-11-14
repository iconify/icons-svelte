<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyuzjqtun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bansuri-flute" {...props}></Icon>
<style>
:global(.uyuzjqtun) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18L18 3a2.25 2.25 0 0 1 3 3L6 21ZM16.5 4.5l3 3m-12 9h.01");
}

</style>
