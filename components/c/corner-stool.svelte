<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2d9ax7jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-stool" {...props}></Icon>
<style>
:global(.a2d9ax7jg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9V7.5c0-3 16-3 16 0V9Zm2.5 0L4 19.5M12 9v10.5M17.5 9L20 19.5");
}

</style>
