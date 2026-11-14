<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="psxwdrbqc"/><path class="zagn_oftx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beetle" {...props}></Icon>
<style>
:global(.psxwdrbqc) {
  d: path("M6.5 13.5a5.5 7 0 1 0 11 0a5.5 7 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zagn_oftx) {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 9v11.5M7.25 10L4 7.5M6.5 14H3m4.75 4L4.5 21m12.25-11L20 7.5M17.5 14H21m-4.75 4l3.25 3");
}

</style>
