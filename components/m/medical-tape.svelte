<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e6tbivszl"/><path class="sb-7ussaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:medical-tape" {...props}></Icon>
<style>
:global(.e6tbivszl) {
  d: path("M2.5 11.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.sb-7ussaf) {
  d: path("M7 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 7.5h11.5v-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
