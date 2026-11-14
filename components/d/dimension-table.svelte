<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ei1kdh0ok"/><path class="n8eb37-va"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dimension-table" {...props}></Icon>
<style>
:global(.ei1kdh0ok) {
  d: path("M3 3h18v18H3Zm0 8h18M3 16h18m-10.5-5v10");
}

:global(.n8eb37-va) {
  d: path("m6.5 7l2-2h8v4h-8l-2-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
