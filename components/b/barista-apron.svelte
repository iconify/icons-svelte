<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b1nthabki"/><path class="jai81ebfo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barista-apron" {...props}></Icon>
<style>
:global(.b1nthabki) {
  d: path("M8 7h8v3.5l3 1.5v8a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20v-8l3-1.5Zm0 0a4 4 0 0 1 8 0M5 12l-2.5 2.5M19 12l2.5 2.5");
}

:global(.jai81ebfo) {
  d: path("M9 15h6v3.5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
