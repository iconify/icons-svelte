<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="yh-9ml9ed"/><path class="c6ohsi9xo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:file-3d" {...props}></Icon>
<style>
:global(.c6ohsi9xo) {
  d: path("m8.5 12.5l3.5 2l3.5-2m-3.5 2v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uwivq1yig) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

:global(.yh-9ml9ed) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-7.5 2l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

</style>
