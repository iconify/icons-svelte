<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1aay2bno"/><path class="vvuwsmbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cork-board-material" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vvuwsmbdi) {
  d: path("M9.5 7h5l-1 3l1.5 2H9l1.5-2Zm2.5 5v3.5m-5 2h.01M17 17h.01");
}

:global(.x1aay2bno) {
  d: path("M3 4h18v17H3Z");
}

</style>
