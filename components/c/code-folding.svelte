<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="blzqlqn5v"/><path class="jtkg58beq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-folding" {...props}></Icon>
<style>
:global(.blzqlqn5v) {
  d: path("M4.5 2.5h15v19h-15Zm0 9.5h15");
}

:global(.jtkg58beq) {
  d: path("M9 6.5L12 9l3-2.5m-6 11l3-2.5l3 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
