<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_oxc8rru"/><path class="zzitdvf-y"/><path class="x2vm17iag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:repost" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_oxc8rru) {
  d: path("M6 6v9.5A2.5 2.5 0 0 0 8.5 18H13");
}

:global(.x2vm17iag) {
  d: path("m15 15l3 3l3-3");
}

:global(.zzitdvf-y) {
  d: path("m3 9l3-3l3 3m2-3h4.5A2.5 2.5 0 0 1 18 8.5V18");
}

</style>
