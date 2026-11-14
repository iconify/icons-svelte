<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="abqnffbdc"/><path class="r_u5cjb_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:brick" {...props}></Icon>
<style>
:global(.abqnffbdc) {
  d: path("m2.5 11l4-5h15v7l-5 5h-14Z");
}

:global(.r_u5cjb_d) {
  d: path("M2.5 11h14l5-5m-5 5v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
