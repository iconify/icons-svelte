<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d6jcy2ovj"/><path class="arg89-b_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-help-duotone-round" {...props}></Icon>
<style>
:global(.arg89-b_m) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11a8 8 0 1 0-8 8m0-12v4h3m1 5a2 2 0 1 1 2 2m0 3h.01");
}

:global(.d6jcy2ovj) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 11h-8v8a8 8 0 1 1 8-8");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
