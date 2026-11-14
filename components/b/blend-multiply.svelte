<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="a_lcojbar"/><path class="nfn4-__am"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blend-multiply" {...props}></Icon>
<style>
:global(.a_lcojbar) {
  d: path("M6.25 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kebju1mox) {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

:global(.nfn4-__am) {
  d: path("M10.75 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
