<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi6v2b-ho"/><path class="btm028itd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:retail-unit" {...props}></Icon>
<style>
:global(.btm028itd) {
  d: path("M8.5 13h7v7.5h-7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vi6v2b-ho) {
  d: path("m3 9l1.5-5h15L21 9Zm1.5 2v9.5h15V11");
}

</style>
