<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ce-wo3bma"/><path class="gjh4r7bsj"/><path class="hcret-b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:corset-lacing" {...props}></Icon>
<style>
:global(.ce-wo3bma) {
  d: path("M4 4q8-2 16 0c-2 5-2 11 0 17q-8 1.5-16 0C6 15 6 9 4 4Z");
}

:global(.gjh4r7bsj) {
  d: path("M9.5 3.25q1.5 8.625 0 18m5-18q-1.5 8.625 0 18");
}

:global(.hcret-b6a) {
  d: path("m10.25 6.5l3.5 3l-3.5 3l3.5 3l-3.5 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
