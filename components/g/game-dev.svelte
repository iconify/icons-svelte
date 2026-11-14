<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n8-i4o31r"/><path class="k3vcnrb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:game-dev" {...props}></Icon>
<style>
:global(.k3vcnrb_m) {
  d: path("M10 7L7.5 9.5L10 12m4-5l2.5 2.5L14 12");
}

:global(.n8-i4o31r) {
  d: path("M4.5 4h15v11h-15Zm0 11l-2 4h19l-2-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
