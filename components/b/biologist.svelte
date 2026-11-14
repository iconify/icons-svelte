<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u3f6fgy0l"/><path class="pmj-49n-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:biologist" {...props}></Icon>
<style>
:global(.pmj-49n-u) {
  d: path("m8.5 15l1.75 3.5l1.75-4l1.75 4L15.5 15");
}

:global(.u3f6fgy0l) {
  d: path("M8 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 21.5c0-4.25 4-7 9-7s9 2.75 9 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
