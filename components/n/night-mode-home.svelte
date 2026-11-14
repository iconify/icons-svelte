<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cb95udksf"/><path class="sz60srb2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:night-mode-home" {...props}></Icon>
<style>
:global(.cb95udksf) {
  d: path("m4 10.5l8-7l8 7v1.75h-7.75V20H4Z");
}

:global(.sz60srb2k) {
  d: path("M21 19.25A3.5 3.5 0 1 1 16.75 15A2.75 2.75 0 0 0 21 19.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
