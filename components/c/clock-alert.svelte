<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d8yu7ob-x"/><path class="hgsa0iwbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clock-alert" {...props}></Icon>
<style>
:global(.d8yu7ob-x) {
  d: path("M2.5 12.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

:global(.hgsa0iwbw) {
  d: path("M10.5 8.5v4L13 14m8-10v5.5m0 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
