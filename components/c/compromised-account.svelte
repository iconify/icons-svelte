<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b0f5_q40h"/><path class="acukmzbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compromised-account" {...props}></Icon>
<style>
:global(.acukmzbyh) {
  d: path("m9.75 3l-1.5 3.5l2.5 2.5l-1.5 4M18 14.5V18m0 3h.01");
}

:global(.b0f5_q40h) {
  d: path("M4.25 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3 21.5C3 18.25 5.5 16 9.25 16c3.016 0 5.223 1.455 5.972 3.716");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
