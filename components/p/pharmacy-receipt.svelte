<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cmtqa2bdd"/><path class="e9fltbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pharmacy-receipt" {...props}></Icon>
<style>
:global(.cmtqa2bdd) {
  d: path("M12.878 20.027L12 19.5L9.5 21l-2.25-1.5L5 21V2.5h14v11.3M8.5 7h7m-7 4H13");
}

:global(.e9fltbcec) {
  d: path("m14.75 18l2 2L21 15.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
