<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_d9uib9w"/><path class="fmt0uc0en"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bound-report" {...props}></Icon>
<style>
:global(.fmt0uc0en) {
  d: path("M10.5 6h6.25v4H10.5Z");
}

:global(.o_d9uib9w) {
  d: path("M4.5 2.5h15v19h-15Zm3.25 0v19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
