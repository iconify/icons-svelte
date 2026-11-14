<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nfysj1bcw"/><path class="ga7qoynrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:plant-wall-frame" {...props}></Icon>
<style>
:global(.ga7qoynrs) {
  d: path("M12 17c0-3-2.5-5-5-5c0 3 2.5 5 5 5Zm0-3.5c0-3 2.5-5 5-5c0 3-2.5 5-5 5Z");
}

:global(.nfysj1bcw) {
  d: path("M3 5h18v15.5H3Zm5.5 0L12 2.5L15.5 5M12 17.5V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
