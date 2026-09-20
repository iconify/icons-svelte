<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="geztznlon"/><path class="f0k-qn7fa"/><path class="zicuro7zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dress-code-outline-regular" {...props}></Icon>
<style>
:global(.f0k-qn7fa) {
  d: path("m20 7 -4 4 4 4Z");
}

:global(.geztznlon) {
  d: path("m4 7 4 4 -4 4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zicuro7zb) {
  d: path("M10 8h4v6h-4Z");
}

</style>
