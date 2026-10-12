<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kf4bnmbrc"/><path class="vsx74xk5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:activity-sharp" {...props}></Icon>
<style>
:global(.kf4bnmbrc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.75h3.5l2.75-8l5.5 15l2.75-7");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vsx74xk5w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 12.75h.01");
}

</style>
