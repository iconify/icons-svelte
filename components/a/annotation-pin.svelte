<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhntk1bbt"/><path class="vlrnd6bmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:annotation-pin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jhntk1bbt) {
  d: path("M5.5 6h13a2 2 0 0 1 2 2v7.5L15 21H5.5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2");
}

:global(.vlrnd6bmo) {
  d: path("M20.5 15.5H17a2 2 0 0 0-2 2V21M10.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12 6v3.5");
}

</style>
