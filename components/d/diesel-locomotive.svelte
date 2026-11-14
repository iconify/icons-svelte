<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mow_f5l_u"/><path class="qw88tgb1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:diesel-locomotive" {...props}></Icon>
<style>
:global(.mow_f5l_u) {
  d: path("M2.5 17V5A1.5 1.5 0 0 1 4 3.5h6v5h10a1.5 1.5 0 0 1 1.5 1.5v7Z");
}

:global(.qw88tgb1a) {
  d: path("M5.5 3.5v5H10m5 0v-3M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
