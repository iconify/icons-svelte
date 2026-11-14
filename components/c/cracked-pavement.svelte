<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ywk-lxbmn"/><path class="f04uoqbvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cracked-pavement" {...props}></Icon>
<style>
:global(.f04uoqbvy) {
  d: path("m17.5 6l-1.75 4l2 3l-2.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ywk-lxbmn) {
  d: path("M6 6h15.5L18 18H2.5Zm7.75 0l-3.5 12");
}

</style>
