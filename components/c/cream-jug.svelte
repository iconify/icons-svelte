<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9qt2mzjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cream-jug" {...props}></Icon>
<style>
:global(.k9qt2mzjg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7h10l-1 10.5c-.2 1.5-1.5 2.5-3 2.5h-2c-1.5 0-2.8-1-3-2.5Zm10 2.5c3 0 3.5 5-.5 5M7 7c1-2.5 2.5-2.5 3.5 0");
}

</style>
