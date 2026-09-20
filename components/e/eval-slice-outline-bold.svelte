<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="eo6vf-b4f"/><path class="u-lzqwb8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:eval-slice-outline-bold" {...props}></Icon>
<style>
:global(.dx3ubrb9h) {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.eo6vf-b4f) {
  d: path("M10.5 10H8v7h2.5");
}

:global(.hbtmd5b0k) {
  d: path("M9.5 7V2.5h5V7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u-lzqwb8v) {
  d: path("M13.5 10H16v7h-2.5");
}

</style>
