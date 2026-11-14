<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hus8yektw"/><path class="jl-908brv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rotate-left" {...props}></Icon>
<style>
:global(.hus8yektw) {
  d: path("M19.5 20.5a13 13 0 0 0-13-13h-2");
}

:global(.jl-908brv) {
  d: path("M8 4L4.5 7.5L8 11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
