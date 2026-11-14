<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lsud0k17c"/><path class="f_6h9wcig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electoral-votes" {...props}></Icon>
<style>
:global(.f_6h9wcig) {
  d: path("m9.75 7.5l1.75 1.75l2.75-3");
}

:global(.lsud0k17c) {
  d: path("M3 12h18v9.5H3Zm4.5 0V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
