<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn04xnb4b"/><path class="e9fltbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:agent-approve" {...props}></Icon>
<style>
:global(.e9fltbcec) {
  d: path("m14.75 18l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zn04xnb4b) {
  d: path("M13.328 20.5H5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T4 19.5v-12q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124t.173-.093t.188-.057T5 6.5h14q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T20 7.5v5.286M12 2.75V6.5m-3 6h.01m5.99 0h.01");
}

</style>
