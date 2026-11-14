<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h98gxob2v"/><path class="rlwzkgbzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:piste-advanced" {...props}></Icon>
<style>
:global(.h98gxob2v) {
  d: path("m13.856 4.356l5.788 5.788a2.625 2.625 0 0 1 0 3.712l-5.788 5.788a2.625 2.625 0 0 1-3.712 0l-5.788-5.788a2.625 2.625 0 0 1 0-3.712l5.788-5.788a2.625 2.625 0 0 1 3.712 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rlwzkgbzv) {
  fill: currentColor;
  d: path("m13.061 8.811l2.128 2.128a1.5 1.5 0 0 1 0 2.122l-2.128 2.128a1.5 1.5 0 0 1-2.122 0l-2.128-2.128a1.5 1.5 0 0 1 0-2.122l2.128-2.128a1.5 1.5 0 0 1 2.122 0");
}

</style>
