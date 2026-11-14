<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r77lclbfk"/><path class="fy5-rvbru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clock-digital" {...props}></Icon>
<style>
:global(.fy5-rvbru) {
  d: path("M5.25 8.25h4v7h-4Zm9.5 0h4v7h-4ZM12 10h.01M12 13.5h.01");
}

:global(.r77lclbfk) {
  d: path("M2.5 5.5h19V18h-19Zm3 12.5v2m13-2v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
