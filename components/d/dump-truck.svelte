<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gkakjv-yy"/><path class="qiq1tzb_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dump-truck" {...props}></Icon>
<style>
:global(.gkakjv-yy) {
  d: path("M4 14.5h17.5v-4l-3-4H15v8");
}

:global(.qiq1tzb_r) {
  d: path("m4 14.5l7.5-4.5l-1.75-3l-7.5 4.5Zm2.5 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
