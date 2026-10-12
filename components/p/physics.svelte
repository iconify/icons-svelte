<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rodzibcla"/><circle class="z2w-83bda"/><path class="z5-oagmmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:physics" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rodzibcla) {
  d: path("M6.75 3.75h10.5m-5.25 0l2.13 8.36");
}

:global(.z2w-83bda) {
  cx: 15px;
  cy: 15.5px;
  r: 2.5px;
}

:global(.z5-oagmmd) {
  d: path("M6.1 19.96a17.25 17.25 0 0 0 11.8 0");
}

</style>
