<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xeahgxpeb"/><path class="h-ng90blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mail-attachment-sharp" {...props}></Icon>
<style>
:global(.h-ng90blk) {
  d: path("m4.5 10.75l2.9 2.2l.85.585l.85-.585l2.9-2.2m9.25-.75V5.25a2.5 2.5 0 0 0-5 0v8.25h2.5v-7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xeahgxpeb) {
  d: path("M2.75 7.25h11v12h-11z");
}

</style>
