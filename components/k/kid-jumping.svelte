<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sm_53ibzd"/><path class="b0mfgjbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kid-jumping" {...props}></Icon>
<style>
:global(.b0mfgjbic) {
  d: path("m5.5 4.5l3.5 6h6l3.5-6m-6.5 6V15m-3.5 3.5L12 15l3.5 3.5m-9 3h11");
}

:global(.sm_53ibzd) {
  d: path("M9.75 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
