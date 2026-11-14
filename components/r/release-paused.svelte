<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nasyt3bce"/><path class="hyiitqbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:release-paused" {...props}></Icon>
<style>
:global(.hyiitqbus) {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10m4.75-5.75v5.75m3.5-5.75v5.75");
}

:global(.nasyt3bce) {
  d: path("M13.976 20.454L12 21.5L3.5 17V7L12 2.5L20.5 7v5.982");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
