<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_29g8b8l"/><path class="p_mj_3-5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:inhaler" {...props}></Icon>
<style>
:global(.p_mj_3-5s) {
  d: path("M9.75 2.5h6v10h-6Zm0 2.5h6m-11 12v2");
}

:global(.s_29g8b8l) {
  d: path("M9 9v5.5H4.5c-1.1 0-2 .9-2 2v3c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
