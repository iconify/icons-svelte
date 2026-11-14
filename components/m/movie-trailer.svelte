<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nk1fobbcd"/><path class="sepjjqblv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:movie-trailer" {...props}></Icon>
<style>
:global(.nk1fobbcd) {
  d: path("M3 3h18v18H3Zm0 3.75h18M3 17.25h18");
}

:global(.sepjjqblv) {
  d: path("m9.5 9l5.5 3l-5.5 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
