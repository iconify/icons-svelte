<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jct3fj_gk"/><path class="rga15fqhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:adware" {...props}></Icon>
<style>
:global(.jct3fj_gk) {
  d: path("M8.5 16h-4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v3.25");
}

:global(.rga15fqhl) {
  d: path("M11.25 11H21.5v9.5H11.25ZM2.5 7h15M15 14.25l3 3m0-3l-3 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
