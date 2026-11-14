<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rzdrhw8yd"/><path class="iozeegaff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auditor-badge" {...props}></Icon>
<style>
:global(.iozeegaff) {
  d: path("m9 16l2 2l4-4");
}

:global(.rzdrhw8yd) {
  d: path("m7 2.5l5 3l5-3m-7 3h4v3h-4Zm-4 3h12v13H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
