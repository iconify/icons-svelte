<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcm31ncqs"/><path class="o4x-zoiyb"/><path class="upewqvbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lock-reset" {...props}></Icon>
<style>
:global(.o4x-zoiyb) {
  d: path("M12 4.5a8.5 8.5 0 1 1-7.361 4.25");
}

:global(.tcm31ncqs) {
  d: path("M8.5 12h7v5.5h-7Zm1.5 0v-1.25a2 2 0 0 1 4 0V12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.upewqvbrp) {
  d: path("m15 2l-3 2.5L15 7m-3 7.75h.01");
}

</style>
