<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y6t8wrg7l"/><path class="g2m7vcbqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kpi-card" {...props}></Icon>
<style>
:global(.g2m7vcbqg) {
  d: path("m6 15l3.5-2.5l3 1.5L18 9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y6t8wrg7l) {
  d: path("M2.5 4.5h19v15h-19ZM6 9h4");
}

</style>
