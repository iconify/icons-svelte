<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7pq6jbac"/><path class="u4wdfl5xf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:desk-tray-stack" {...props}></Icon>
<style>
:global(.i7pq6jbac) {
  d: path("M2.5 6.5v3h19v-3m-19 6v3h19v-3m-19 6v3h19v-3");
}

:global(.u4wdfl5xf) {
  d: path("M6.5 9.5V3h11v6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
