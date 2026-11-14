<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="keo0j_bal"/><path class="gn_79dbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cocoon" {...props}></Icon>
<style>
:global(.gn_79dbkv) {
  d: path("M7.25 11q4.75 2.5 9.5 0m-9.5 5q4.75 2.5 9.5 0");
}

:global(.keo0j_bal) {
  d: path("M7 13.5a5 7.5 0 1 0 10 0a5 7.5 0 1 0-10 0Zm5-11V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
