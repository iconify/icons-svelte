<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="av8i1cgfc"/><path class="l2ceo8b6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:obsidian" {...props}></Icon>
<style>
:global(.av8i1cgfc) {
  d: path("M3.5 17L7 6l6-3.5l7.5 6L17 21Z");
}

:global(.l2ceo8b6x) {
  d: path("M13 2.5L11.5 12l5.5 9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
