<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nr2fehbzj"/><path class="ssti27bmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:machete" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nr2fehbzj) {
  d: path("M8.75 13.25L18.5 3.5c1.5-1.5 3-1 2.75 1.25C19.5 9.25 15 13 11 15.5Zm-1-1l4 4");
}

:global(.ssti27bmm) {
  d: path("M9.975 14.025za1.75 1.75 0 0 1 0 2.475L7.5 18.975a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475L7.5 14.025a1.75 1.75 0 0 1 2.475 0");
}

</style>
