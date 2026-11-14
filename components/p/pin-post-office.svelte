<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u7rafmb9c"/><path class="w35n61kja"/><path class="msad3isat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-post-office" {...props}></Icon>
<style>
:global(.msad3isat) {
  d: path("m8 12l4 3l4-3");
}

:global(.u7rafmb9c) {
  d: path("M2.5 9L12 3l9.5 6Zm2 0v12h15V9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w35n61kja) {
  d: path("M8 12h8v6H8Z");
}

</style>
