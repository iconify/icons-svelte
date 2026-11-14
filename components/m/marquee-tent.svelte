<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7xwwuvxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marquee-tent" {...props}></Icon>
<style>
:global(.b7xwwuvxc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9.5l9-7l9 7m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-18 0v12m18-12v12m-13 0l4-7l4 7");
}

</style>
