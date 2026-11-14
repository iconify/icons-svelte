<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="go6eaachx"/><path class="is9z-p8nm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mouse-check" {...props}></Icon>
<style>
:global(.go6eaachx) {
  d: path("M10 3h4a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 14 21h-4a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 10 3Zm2 3.5v3");
}

:global(.is9z-p8nm) {
  d: path("m9.75 14.5l1.5 1.5l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
