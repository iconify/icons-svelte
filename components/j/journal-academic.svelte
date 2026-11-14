<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="in945rb_y"/><path class="f1ha8jb-a"/><path class="lszvceb3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:journal-academic" {...props}></Icon>
<style>
:global(.f1ha8jb-a) {
  d: path("m14 5.5l3.25 1.75L14 9l-3.25-1.75Z");
}

:global(.in945rb_y) {
  d: path("M4 2.5h16v19H4Zm3.5 0v19");
}

:global(.lszvceb3m) {
  d: path("M12 8v2.5q2 1.25 4 0V8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
