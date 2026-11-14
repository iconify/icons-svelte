<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="my-xoquju"/><path class="xhtl5655l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ortho-wax" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.my-xoquju) {
  d: path("M7 2.5c2 0 3 1 5 1s3-1 5-1c2.5 0 4 2 4 5s-1.25 5-1.75 7.5l-1 5c-.25 1.5-2 1.75-2.5.5l-1.75-4c-.5-1-3.5-1-4 0l-1.75 4c-.5 1.25-2.25 1-2.5-.5l-1-5C4.25 12.5 3 10.5 3 7.5s1.5-5 4-5");
}

:global(.xhtl5655l) {
  d: path("M9 9.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2.75 0H9m6 0h2.75");
}

</style>
