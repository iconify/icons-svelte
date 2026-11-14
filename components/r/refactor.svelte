<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5jo19m1a"/><path class="xddcc2bdh"/><path class="t5mofjtby"/><path class="qupeo_3fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:refactor" {...props}></Icon>
<style>
:global(.d5jo19m1a) {
  d: path("M8.5 8.5h7v7h-7Z");
}

:global(.qupeo_3fy) {
  d: path("m10 2l2 2l-2 2");
}

:global(.t5mofjtby) {
  d: path("m14 18l-2 2l2 2m-6-3.072A8 8 0 0 1 12 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xddcc2bdh) {
  d: path("M16 5.072A8 8 0 0 1 12 20");
}

</style>
