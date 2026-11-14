<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d85880qim"/><path class="c57a8o-tr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:returns-desk" {...props}></Icon>
<style>
:global(.c57a8o-tr) {
  d: path("m16.5 14.25l-2 2l2 2");
}

:global(.d85880qim) {
  d: path("M2.5 11h13.3m1.4 0h4.3M4 11v10.5h11.8m1.4 0h1.5m1.3-8V11M4 18.5h7.7M6 4.5h7V11H6Zm3.5 0V7m12 14.25v-2.5a2.5 2.5 0 0 0-2.5-2.5h-4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
