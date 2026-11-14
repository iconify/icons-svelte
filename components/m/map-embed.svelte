<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3qj1hboj"/><path class="rm2dge7vs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-embed" {...props}></Icon>
<style>
:global(.o3qj1hboj) {
  d: path("M12.09 19.526L8.5 18.5l-6 2v-15l6-2l7 2l6-2v9.571M8.5 3.5v15m7-13v5.7");
}

:global(.rm2dge7vs) {
  d: path("m16 15l-2 2.5l2 2.5m3.5-5l2 2.5l-2 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
