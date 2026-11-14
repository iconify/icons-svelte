<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id95gub5u"/><path class="tkz7rmbsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-saver-video" {...props}></Icon>
<style>
:global(.id95gub5u) {
  d: path("M14.1 15.5H2.5v-12h17v8.2");
}

:global(.tkz7rmbsw) {
  d: path("M8.5 6.25L14 9.5l-5.5 3.25ZM18 14.5v7m-3-3l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
