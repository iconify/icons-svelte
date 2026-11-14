<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_rvjt7dj"/><path class="ka-t9s-zl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hockey-scoreboard" {...props}></Icon>
<style>
:global(.ka-t9s-zl) {
  d: path("M5.5 6.5h4v5h-4Zm9 0h4v5h-4ZM12 7.75h.01m-.01 2.5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_rvjt7dj) {
  d: path("M2.5 3.5h19v11h-19Zm2.5 11v7m14-7v7");
}

</style>
