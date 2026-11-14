<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vbvo3xvxs"/><path class="cnsb5n80n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:repo-clone" {...props}></Icon>
<style>
:global(.cnsb5n80n) {
  d: path("M3 17V4.5a2 2 0 0 1 2-2h12m-6.25 4v15M14 6.5v5l1.75-1.25l1.75 1.25v-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vbvo3xvxs) {
  d: path("M7.5 6.5H21v15H7.5Z");
}

</style>
