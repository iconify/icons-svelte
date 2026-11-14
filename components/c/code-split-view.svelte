<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iiwnuubed"/><path class="h0okt56_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-split-view" {...props}></Icon>
<style>
:global(.h0okt56_g) {
  d: path("m8.75 8.5l-3 3.5l3 3.5m6.5-7l3 3.5l-3 3.5");
}

:global(.iiwnuubed) {
  d: path("M2.5 4h19v16h-19ZM12 4v16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
