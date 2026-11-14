<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bnutvgb7t"/><path class="offgktbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-arrow-u-turn" {...props}></Icon>
<style>
:global(.bnutvgb7t) {
  d: path("M18 21.5V9A5 5 0 0 0 8 9v9.5");
}

:global(.offgktbzi) {
  d: path("M4.5 15L8 18.5l3.5-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
