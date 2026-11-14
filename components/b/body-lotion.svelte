<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvq0nnb2g"/><path class="m87kyus6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:body-lotion" {...props}></Icon>
<style>
:global(.m87kyus6u) {
  d: path("M12 12.75s1.5 1.75 1.5 2.75a1.5 1.5 0 0 1-3 0c0-1 1.5-2.75 1.5-2.75Z");
}

:global(.mvq0nnb2g) {
  d: path("M6.5 10.5h11V21h-11Zm3.5 0V8h4v2.5M12 8V4.5h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
