<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j1-ukck7n"/><path class="f8iztobqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-americium" {...props}></Icon>
<style>
:global(.f8iztobqm) {
  d: path("M8 9.25h8v5.5H8ZM9 18h6");
}

:global(.j1-ukck7n) {
  d: path("M3.5 3h17v18h-17Zm3 3.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
