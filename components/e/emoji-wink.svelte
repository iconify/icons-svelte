<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zt30-rrpj"/><path class="wbzl-n3-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:emoji-wink" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbzl-n3-e) {
  d: path("M13.5 10.5c.75-1 2.25-1 3 0m-8 4c1 1.5 2.1 2.25 3.5 2.25s2.5-.75 3.5-2.25");
}

:global(.zt30-rrpj) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 10h.01");
}

</style>
