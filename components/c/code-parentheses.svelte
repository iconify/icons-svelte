<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn_7-5b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-parentheses" {...props}></Icon>
<style>
:global(.xn_7-5b9p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5c-4 4-4 13 0 17m6-17c4 4 4 13 0 17");
}

</style>
