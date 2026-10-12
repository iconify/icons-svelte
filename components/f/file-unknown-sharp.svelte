<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s43l187bp"/><path class="i51gaebsn"/><path class="sdppemtic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-unknown-sharp" {...props}></Icon>
<style>
:global(.i51gaebsn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5M10 12.5a2 2 0 1 1 2.75 1.85l-.75.333v1.067");
}

:global(.s43l187bp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.sdppemtic) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
