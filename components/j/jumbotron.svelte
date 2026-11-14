<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umn_pbcqh"/><path class="j8q-tib6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:jumbotron" {...props}></Icon>
<style>
:global(.j8q-tib6t) {
  d: path("m10 6.5l5.5 3l-5.5 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umn_pbcqh) {
  d: path("M2.5 2.5h19v14h-19Zm4.5 14v5m10-5v5");
}

</style>
