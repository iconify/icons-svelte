<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z7scqubjs"/><path class="qkgn0lbks"/><path class="onhtdubic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:display-podium" {...props}></Icon>
<style>
:global(.onhtdubic) {
  d: path("M7.5 3h9v8.5h-9Zm0 3h9M12 3v3");
}

:global(.qkgn0lbks) {
  d: path("M4 13.5a8 2.75 0 1 0 16 0a8 2.75 0 1 0-16 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z7scqubjs) {
  d: path("M4 13.5v5a8 2.75 0 0 0 16 0v-5");
}

</style>
