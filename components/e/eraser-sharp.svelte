<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jw_womwek"/><path class="qiyt7qmru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eraser-sharp" {...props}></Icon>
<style>
:global(.jw_womwek) {
  d: path("m18.65 7.54l-3.19-3.19l-.88-.88l-.88.88l-3.54 3.55l-.88.88l.88.88l3.18 3.18l.88.88l.88-.88l3.55-3.54l.88-.88z");
}

:global(.qiyt7qmru) {
  d: path("m13.34 12.84l-3.18-3.18l-.88-.88l-.89.88l-2.11 2.12l-.89.88l.88.88l3.19 3.19l.88.88l.88-.89l2.12-2.11l.88-.89zM11 20.25h9.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
