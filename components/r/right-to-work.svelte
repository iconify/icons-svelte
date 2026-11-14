<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ddw0uq-1u"/><path class="gko6xgb5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:right-to-work" {...props}></Icon>
<style>
:global(.ddw0uq-1u) {
  d: path("M8.75 8.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.eoz3zibrm) {
  d: path("M4.5 2.5h15v19h-15Z");
}

:global(.gko6xgb5f) {
  d: path("M10.75 8.5a1.25 3.25 0 1 0 2.5 0a1.25 3.25 0 1 0-2.5 0ZM9 16.5l2 2l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
