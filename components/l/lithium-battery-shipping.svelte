<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6ux0ccgi"/><path class="v_jv31vjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lithium-battery-shipping" {...props}></Icon>
<style>
:global(.l6ux0ccgi) {
  d: path("M4 7h14v10H4Zm14 3v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_jv31vjr) {
  d: path("M10 8.5L8 12h4l-2 3.5");
}

</style>
