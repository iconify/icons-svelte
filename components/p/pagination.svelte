<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bigsk3vgs"/><path class="dvr-mgrti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pagination" {...props}></Icon>
<style>
:global(.bigsk3vgs) {
  fill: currentColor;
  d: path("M3 10h8v4H3Z");
}

:global(.dvr-mgrti) {
  d: path("M15 12h.01M20 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
