<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e6t-mdbow"/><path class="qlmr8fbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:air-base" {...props}></Icon>
<style>
:global(.e6t-mdbow) {
  d: path("M2.5 15.5v-4a9.5 7 0 0 1 19 0v4Z");
}

:global(.qlmr8fbah) {
  d: path("M7.5 15.5V11h9v4.5M4 19.5h3.5m2.75 0h3.5m2.75 0H20");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
