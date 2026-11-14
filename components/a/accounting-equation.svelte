<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f114febcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:accounting-equation" {...props}></Icon>
<style>
:global(.f114febcq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-4 0h8M5.5 6h13m-16 7l3-7l3 7Zm0 0a3 3 0 0 0 6 0m7 0l3-7l3 7Zm0 0a3 3 0 0 0 6 0");
}

</style>
