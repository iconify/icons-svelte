<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rhf_fek-r"/><path class="bdlmm7bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:formula-bar" {...props}></Icon>
<style>
:global(.bdlmm7bix) {
  d: path("M8.75 9c-.5-.25-1.25-.25-1.5.5l-.5 4.5c-.25 1-.75 1.25-1.5 1m0-4h3m.75.25l2.25 3m0-3l-2.25 3m4.25-6.75v9m2.5-4.5H19");
}

:global(.rhf_fek-r) {
  d: path("M2 7.5h20v9H2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
