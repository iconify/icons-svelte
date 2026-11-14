<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="de4txlbkz"/><path class="zip6x2byd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:playhouse" {...props}></Icon>
<style>
:global(.de4txlbkz) {
  d: path("M13.16 20.5H4v-10l8-7l8 7v3.24");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zip6x2byd) {
  d: path("M16 7V4h2v4.75m-2 5.75l5.5 3.5l-5.5 3.5Z");
}

</style>
