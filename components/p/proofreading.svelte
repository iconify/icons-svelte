<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n37nsl_xt"/><path class="q1wf-h50c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:proofreading" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n37nsl_xt) {
  d: path("M2.5 3H17M2.5 21H12m-4-8.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m9.5 4L21 20");
}

:global(.q1wf-h50c) {
  d: path("m11.25 12.5l1.5 1.5l3-3");
}

</style>
