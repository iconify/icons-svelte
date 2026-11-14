<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivfv54j6s"/><path class="efl79dbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bee-hive-garden" {...props}></Icon>
<style>
:global(.efl79dbbw) {
  d: path("M10.25 20.5v-1a1.75 1.75 0 0 1 3.5 0v1m-11.25 0h19");
}

:global(.ivfv54j6s) {
  d: path("M3.5 15h17v5.5h-17Zm2-5.5h13V15h-13ZM8 4h8v5.5H8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
