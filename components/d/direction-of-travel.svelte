<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fd-zl2k6q"/><path class="zp_iseblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:direction-of-travel" {...props}></Icon>
<style>
:global(.fd-zl2k6q) {
  d: path("M2.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0c6 0 6.5-11.5 14-11.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zp_iseblh) {
  d: path("m17.5 3.5l3 3l-3 3");
}

</style>
