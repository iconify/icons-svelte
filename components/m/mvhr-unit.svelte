<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4-lfx72e"/><path class="s8mod7bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mvhr-unit" {...props}></Icon>
<style>
:global(.d4-lfx72e) {
  d: path("M2.5 5h19v14h-19ZM6 9.25h12");
}

:global(.s8mod7bty) {
  d: path("m16.5 7.75l1.5 1.5l-1.5 1.5m-10.5 4h12m-10.5-1.5L6 14.75l1.5 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
