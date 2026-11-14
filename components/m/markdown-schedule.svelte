<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rkti75iui"/><path class="nc_mmcbkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:markdown-schedule" {...props}></Icon>
<style>
:global(.nc_mmcbkp) {
  d: path("M14.5 15.25h7v6.5h-7Zm0 2.5h7m-5-3.75v1.75m3-1.75v1.75");
}

:global(.rkti75iui) {
  d: path("M11.7 19.5H8.5l-5-7.5l5-7.5h11v6.7M8.25 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
