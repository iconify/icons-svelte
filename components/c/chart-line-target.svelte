<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xjxxwsbnq"/><path class="ochqaij3u"/><path class="u5eh67bxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-line-target" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ochqaij3u) {
  fill: currentColor;
  d: path("m18.879 3.091l.371.159a.816.816 0 0 1 0 1.5l-.371.159A.99.99 0 0 1 17.5 4a.99.99 0 0 1 1.379-.909");
}

:global(.u5eh67bxn) {
  d: path("M2.5 9h2M7 9h2m2.5 0h2m6.25 0h1.75");
}

:global(.xjxxwsbnq) {
  d: path("M2.5 20L7 14.5l3.5 2l5-6.5m2-1V2.5");
}

</style>
