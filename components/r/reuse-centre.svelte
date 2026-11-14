<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bkwzcqb9a"/><path class="m3johub1v"/><path class="d-i7hzbjk"/><path class="oyv3cxbac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reuse-centre" {...props}></Icon>
<style>
:global(.bkwzcqb9a) {
  d: path("M3 21V9l9-6l9 6v12Z");
}

:global(.d-i7hzbjk) {
  d: path("m13.25 12.25l1.5.75l.75-1.5Zm1.5 2.75a3 3 0 0 1-5.5 0");
}

:global(.m3johub1v) {
  d: path("M9.25 13a3 3 0 0 1 5.5 0");
}

:global(.oyv3cxbac) {
  d: path("M10.75 15.75L9.25 15l-.75 1.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
