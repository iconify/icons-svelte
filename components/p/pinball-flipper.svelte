<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_9bk5blo"/><path class="ikcoc_bvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pinball-flipper" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikcoc_bvv) {
  d: path("M9 7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6 17h.01");
}

:global(.z_9bk5blo) {
  d: path("M4.75 14L19 7.25a1.25 1.25 0 0 1 1.25 2.25L8 19.5A3.25 3.25 0 1 1 4.75 14");
}

</style>
