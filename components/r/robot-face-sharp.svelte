<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wtrnw5zoe"/><path class="mg_q2s1ic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:robot-face-sharp" {...props}></Icon>
<style>
:global(.mg_q2s1ic) {
  d: path("M7 8.75h3.25v3H7zm6.75 0H17v3h-3.25zM8 14.25h8V17H8zm2.75 0V17m2.5-2.75V17");
}

:global(.wtrnw5zoe) {
  d: path("M3.25 4.25h17.5v15.5H3.25z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
