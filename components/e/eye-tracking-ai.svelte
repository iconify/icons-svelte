<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-cd1pbsv"/><path class="qrech44rr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-tracking-ai" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qrech44rr) {
  d: path("M8 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m7 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-1 0h8m-4-4v8");
}

:global(.w-cd1pbsv) {
  d: path("M12.787 15.353A10.5 10.5 0 0 1 11 15.5c-4 0-6.75-2-8.5-6c1.75-4 4.5-6 8.5-6s6.75 2 8.5 6q-.417.953-.91 1.754");
}

</style>
