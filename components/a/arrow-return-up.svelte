<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c2z2nuu0k"/><path class="yj3kwjbbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-return-up" {...props}></Icon>
<style>
:global(.c2z2nuu0k) {
  d: path("M5.5 9v5.5a4.5 4.5 0 0 0 9 0v-10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yj3kwjbbo) {
  d: path("m10.5 8.5l4-4l4 4");
}

</style>
