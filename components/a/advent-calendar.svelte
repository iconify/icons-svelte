<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf4yyqbpx"/><path class="ytx4uxopf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:advent-calendar" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytx4uxopf) {
  d: path("m9 9.5l2.75 1.5v3M18 18h.01");
}

:global(.zf4yyqbpx) {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4m-13 3h18M3 15h18M9 9.5V21m6-11.5V21");
}

</style>
