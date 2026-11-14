<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ztahwqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:decimal-increase" {...props}></Icon>
<style>
:global(.y0ztahwqq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5h.01M7.5 14a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0m7 0a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0M4 6h16m-2.5-2.5L20 6l-2.5 2.5");
}

</style>
