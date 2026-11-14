<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v6u8rtb_l"/><path class="rfx29db4d"/><path class="cxojlr4il"/><path class="n3n76zkys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coil-spring" {...props}></Icon>
<style>
:global(.cxojlr4il) {
  d: path("M6.5 13.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Z");
}

:global(.n3n76zkys) {
  d: path("M6.5 17.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Zm0 2.5v1.5");
}

:global(.rfx29db4d) {
  d: path("M6.5 9.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6u8rtb_l) {
  d: path("M6.5 5.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Z");
}

</style>
