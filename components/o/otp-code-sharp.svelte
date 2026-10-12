<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bnnqwchkd"/><path class="p2pcalb3f"/><path class="pvh7ewp6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:otp-code-sharp" {...props}></Icon>
<style>
:global(.bnnqwchkd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.75h15v18.5h-15z");
}

:global(.p2pcalb3f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 12h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

:global(.pvh7ewp6v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18.25h3");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
