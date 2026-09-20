<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-4bk_b4n"/><path class="zm2dyvb-o"/><path class="kk7jzcbcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:insight-outline-regular" {...props}></Icon>
<style>
:global(.kk7jzcbcv) {
  d: path("M10 19h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
