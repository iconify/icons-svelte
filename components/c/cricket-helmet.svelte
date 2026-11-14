<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zn_e_hboj"/><path class="i64wkrq6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cricket-helmet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i64wkrq6e) {
  d: path("M13 18.75h3.5c2.5 0 4-3 4-6.5m-3.75 0v6.5");
}

:global(.zn_e_hboj) {
  d: path("M3.5 18.75v-4.5c0-5.25 4-9 9-9c4.25 0 7.25 3 8 7H13v6.5Z");
}

</style>
