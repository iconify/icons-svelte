<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwkz7acvc"/><path class="m4m_dv0ma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:galley-oven" {...props}></Icon>
<style>
:global(.m4m_dv0ma) {
  d: path("M6.5 11.5h11v6h-11ZM7 5.75h.01m3.49 0h.01");
}

:global(.mwkz7acvc) {
  d: path("M2.5 3h19v17.5h-19Zm0 5.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
