<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nztt-wbdv"/><path class="vzm1rd2ai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:metro-card-sharp" {...props}></Icon>
<style>
:global(.nztt-wbdv) {
  d: path("M2.75 5.25h18.5v13.5H2.75zm3.5 4h4.5m-4.5 5.5h3");
}

:global(.vzm1rd2ai) {
  d: path("m14.5 10l2.119 2l-2.119 2M17 8.25a5.25 5.25 0 0 1 0 7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
