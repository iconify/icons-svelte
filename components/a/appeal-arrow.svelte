<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufdvj9kcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:appeal-arrow" {...props}></Icon>
<style>
:global(.ufdvj9kcn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V18q0-1 1-1h4q1 0 1-1v-1.5q0-1 1-1h4q1 0 1-1V11q0-1 1-1h4.5q1 0 1 1v9.25q0 1-1 1H3.75q-1 0-1-1M4 12.5l8-8m-4.5 0H12V9");
}

</style>
