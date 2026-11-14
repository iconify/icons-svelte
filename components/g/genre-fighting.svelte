<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xsrxi7ywh"/><path class="d4xru-dqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-fighting" {...props}></Icon>
<style>
:global(.d4xru-dqx) {
  d: path("M4.75 9.5c2.75-.5 5 .75 5.5 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xsrxi7ywh) {
  d: path("M8 21.5V16c-2.25-1.25-3.5-3.25-3.5-6c0-4.25 3.5-7.5 8-7.5c4 0 7 3 7 7v12ZM8 16h11.5");
}

</style>
