<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g26yyubzh"/><path class="okzqxcb7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-point-right" {...props}></Icon>
<style>
:global(.g26yyubzh) {
  d: path("M12 7h8a1.25 1.25 0 0 1 0 2.5h-6a1.25 1.25 0 0 1 0 2.5a1.25 1.25 0 0 1 0 2.5a1.25 1.25 0 0 1 0 2.5H8.5c-3 0-5.25-2-5.25-5v-1c0-2.25 1.75-4 4-4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.okzqxcb7f) {
  d: path("M6.25 11c1.75-.5 3.25-.5 5 .25");
}

</style>
