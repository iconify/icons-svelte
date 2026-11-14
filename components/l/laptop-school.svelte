<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="guvqp3f2r"/><path class="j4340pbsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:laptop-school" {...props}></Icon>
<style>
:global(.guvqp3f2r) {
  d: path("M7.125 4.5h9.75A2.625 2.625 0 0 1 19.5 7.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 12.875v-5.75A2.625 2.625 0 0 1 7.125 4.5M2.5 18.5h19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4340pbsj) {
  d: path("M7.5 9L12 6.5L16.5 9L12 11.5Zm7 1.25v2.25");
}

</style>
