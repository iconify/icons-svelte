<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oi48jlbdw"/><path class="nqd_99bcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:paper-towel" {...props}></Icon>
<style>
:global(.nqd_99bcy) {
  d: path("M5.5 2.5h13a2.5 4.5 0 0 1 0 9h-13m4 0v9l2-1l2 1.5l2-1.5l2 1.5v-9.5");
}

:global(.oi48jlbdw) {
  d: path("M3 7a2.5 4.5 0 1 0 5 0a2.5 4.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
