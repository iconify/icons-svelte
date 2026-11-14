<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bppgoccny"/><path class="erbb8objb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:butter-tub" {...props}></Icon>
<style>
:global(.bppgoccny) {
  d: path("M3.5 15V9l3-3h7v6l-3 3Zm13-7H20v7h-3.5Zm-14 7h19c-1 3-3 3.5-5.5 3.5H8c-2.5 0-4.5-.5-5.5-3.5Z");
}

:global(.erbb8objb) {
  d: path("M3.5 9h7l3-3m-3 3v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
