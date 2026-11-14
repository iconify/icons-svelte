<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0xwa_byh"/><path class="ambjqxbvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fact-check-x" {...props}></Icon>
<style>
:global(.ambjqxbvt) {
  d: path("m7 10l2.5 2.5l5-5m1 8l5 5m0-5l-5 5");
}

:global(.i0xwa_byh) {
  d: path("M11.6 20.5H3.5v-18H19v10.6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
