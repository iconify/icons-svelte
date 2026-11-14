<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ik9xqux_v"/><path class="yil3u-b5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-merge" {...props}></Icon>
<style>
:global(.ik9xqux_v) {
  d: path("M12 3v8l-6 6v4m6-10l6 6v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yil3u-b5j) {
  d: path("M8.5 6.5L12 3l3.5 3.5");
}

</style>
