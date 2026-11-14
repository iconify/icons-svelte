<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="huk256b0l"/><path class="k003_9bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:farm-iot" {...props}></Icon>
<style>
:global(.huk256b0l) {
  d: path("M10.5 12.5h3V18L12 20.5L10.5 18Zm-7 5.5h4.25m8.5 0h4.25M10 9a2.75 2.75 0 0 1 4 0M8 7a5.75 5.75 0 0 1 8 0");
}

:global(.k003_9bml) {
  d: path("M6 5a8.5 8.5 0 0 1 12 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
