<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d3_jxlben"/><path class="s_7mp1bba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:filter-reminder" {...props}></Icon>
<style>
:global(.d3_jxlben) {
  d: path("M11.1 19.5H2.5v-17h17v9.1M7 6.5v9m4-9v9m4-9v6");
}

:global(.s_7mp1bba) {
  d: path("M14.5 20c1-1 1-2 1-3a2.75 2.75 0 0 1 5.5 0c0 1 0 2 1 3Zm2.75 2h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
