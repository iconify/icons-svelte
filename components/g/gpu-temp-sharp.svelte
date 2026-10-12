<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uv3sb_hzn"/><path class="twkz_8byw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gpu-temp-sharp" {...props}></Icon>
<style>
:global(.twkz_8byw) {
  d: path("M6.5 10h4v4h-4Zm0-6.75v3.5m4-3.5v3.5m-4 10.5v3.5m4-3.5v3.5m5.75-15.5V3.5h3.5v10.85a3 3 0 1 1-3.5 0Z");
}

:global(.uv3sb_hzn) {
  d: path("M3.25 6.75h10.5v10.5H3.25z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
