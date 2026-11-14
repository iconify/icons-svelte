<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wwozeg7ww"/><path class="tfd2rkbmf"/><path class="t4qxwab-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gauge-medium" {...props}></Icon>
<style>
:global(.t4qxwab-a) {
  d: path("M12 14V8.25M15 18h6");
}

:global(.tfd2rkbmf) {
  fill: currentColor;
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wwozeg7ww) {
  d: path("M3 14a9 9 0 0 1 18 0");
}

</style>
