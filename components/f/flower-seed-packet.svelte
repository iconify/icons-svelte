<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbd8vwb8p"/><path class="nnrkuebwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flower-seed-packet" {...props}></Icon>
<style>
:global(.nnrkuebwj) {
  d: path("M12 7.5a2 2 0 0 1 3.25 1.75a2 2 0 0 1 0 4A2 2 0 0 1 12 15a2 2 0 0 1-3.25-1.75a2 2 0 0 1 0-4A2 2 0 0 1 12 7.5Zm0 3.75h.01M12 15v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbd8vwb8p) {
  d: path("m5 4.5l1.75-2l1.75 2l1.75-2l1.75 2l1.75-2l1.75 2l1.75-2l1.75 2v15a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

</style>
