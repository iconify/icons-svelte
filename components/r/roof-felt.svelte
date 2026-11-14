<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ov2ka0vck"/><path class="ehcngrjeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roof-felt" {...props}></Icon>
<style>
:global(.ehcngrjeu) {
  d: path("M4 5v14a5 2.5 0 0 0 10 0V5m0 1.5c4.5 0 6.5 2.5 6.5 6.5v8.5");
}

:global(.ov2ka0vck) {
  d: path("M4 5a5 2.5 0 1 0 10 0A5 2.5 0 1 0 4 5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
