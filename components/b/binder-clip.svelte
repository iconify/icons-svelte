<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crmehveme"/><path class="pb6y1e38y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:binder-clip" {...props}></Icon>
<style>
:global(.crmehveme) {
  d: path("M7.5 8h-1a2 2 0 0 0-2 2v9.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2h-1");
}

:global(.pb6y1e38y) {
  d: path("M7.5 6.5h9V12h-9Zm1 0l-2-4h4v4m5 0l2-4h-4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
