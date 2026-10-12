<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f2v1mybid"/><path class="n-ti9jbti"/><path class="xbpg6ubac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bandage-sharp" {...props}></Icon>
<style>
:global(.f2v1mybid) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.46 13.24l7.78-7.78l2.65-2.647l2.65 2.647l2.647 2.65l-2.647 2.65l-7.78 7.78l-2.65 2.647l-2.65-2.647l-2.647-2.65z");
}

:global(.n-ti9jbti) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.76 10.94l3.18-3.18l.705-.701l.705.701l3.89 3.89l.701.705l-.701.705l-3.18 3.18l-.705.701l-.705-.701l-3.89-3.89l-.701-.705z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xbpg6ubac) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.58 16.42h.01m8.83-8.84h.01");
}

</style>
