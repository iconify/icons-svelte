<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcg2xu7sp"/><path class="i053ffbpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dpad-right" {...props}></Icon>
<style>
:global(.i053ffbpq) {
  fill: currentColor;
  d: path("M15 9h6v6h-6Z");
}

:global(.jcg2xu7sp) {
  d: path("M9 3h6v6h6v6h-6v6H9v-6H3V9h6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
