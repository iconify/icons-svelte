<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cutacbclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alfajores" {...props}></Icon>
<style>
:global(.cutacbclo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5C3 5 21 5 21 9.5Zm0 5h18c0 4-18 4-18 0m2-5q-2.5 2.5 0 5m14-5q2.5 2.5 0 5");
}

</style>
