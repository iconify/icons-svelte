<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrpt_h7co"/><path class="clxcn6bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-scorecard" {...props}></Icon>
<style>
:global(.clxcn6bix) {
  d: path("m8.5 6l4 1.5l-4 1.5Zm0 9h7m-7 3.5h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrpt_h7co) {
  d: path("M4.5 2.5h15v19h-15Zm4 3.5v5.5");
}

</style>
