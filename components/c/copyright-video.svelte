<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="arwzxcbgg"/><path class="c-h46ebis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:copyright-video" {...props}></Icon>
<style>
:global(.arwzxcbgg) {
  d: path("M12.7 19H2.5V5h19v8.5");
}

:global(.c-h46ebis) {
  d: path("m10 9l5 3l-5 3Zm5.5 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
