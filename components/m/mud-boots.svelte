<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8n2ojojw"/><path class="eclr8n6cx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mud-boots" {...props}></Icon>
<style>
:global(.e8n2ojojw) {
  d: path("M5.5 3h7v10l5 2.5l1.5 2v3H5.5Zm0 3h7");
}

:global(.eclr8n6cx) {
  d: path("M5.5 14c1.5 1.5 3-1 4.5.5c1 1 2-.5 3.5-1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
