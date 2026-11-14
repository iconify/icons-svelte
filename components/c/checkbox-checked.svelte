<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lw6t35brr"/><path class="m2g2-tdsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:checkbox-checked" {...props}></Icon>
<style>
:global(.lw6t35brr) {
  d: path("M4 4h16v16H4Z");
}

:global(.m2g2-tdsd) {
  d: path("m7.75 12l3 3l5.5-5.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
