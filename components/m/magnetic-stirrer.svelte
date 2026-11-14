<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jzowre_ua"/><path class="ui9o21fsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magnetic-stirrer" {...props}></Icon>
<style>
:global(.jzowre_ua) {
  d: path("M6 3v16a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V3M6 9h12");
}

:global(.ui9o21fsi) {
  d: path("M9 15.75h6v2.5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
