<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vxkx5oxii"/><path class="u7ej9pbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:risk-trend" {...props}></Icon>
<style>
:global(.u7ej9pbsk) {
  d: path("M16 6.5h4.5V11m-17 10h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vxkx5oxii) {
  d: path("M3.5 18L9 12l4 3.5l7.5-9");
}

</style>
