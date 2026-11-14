<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6bmv3q-h"/><path class="zpfgxsktr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-bar-negative" {...props}></Icon>
<style>
:global(.c6bmv3q-h) {
  d: path("M2.5 12h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpfgxsktr) {
  fill: currentColor;
  d: path("M4 5h1.75v7H4Zm5 7h1.75v6H9Zm5-9h1.75v9H14Zm5 9h1.75v8H19Z");
}

</style>
