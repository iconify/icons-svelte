<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zp5uwxegi"/><path class="zuo752-mb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:graduate-program" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zp5uwxegi) {
  d: path("m12 5l9 4.5l-9 4.5l-9-4.5Z");
}

:global(.zuo752-mb) {
  d: path("M7 12v4.5c1.5 1.25 3.25 1.75 5 1.75s3.5-.5 5-1.75V12m3-2v5");
}

</style>
