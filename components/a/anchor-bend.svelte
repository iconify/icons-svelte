<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d0o4aecsk"/><path class="rlf9gvuii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:anchor-bend" {...props}></Icon>
<style>
:global(.d0o4aecsk) {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2V21m-7.5-7a7.5 7.5 0 0 0 15 0M8 9.5h8");
}

:global(.rlf9gvuii) {
  d: path("M11 4.5h5c2 0 2.5 2.5 4.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
