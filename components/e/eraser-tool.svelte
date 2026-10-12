<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yla1m8bvl"/><path class="lpd--ub5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eraser-tool" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lpd--ub5y) {
  d: path("m13.34 12.84l-3.18-3.18q-.88-.88-1.77 0l-2.11 2.12q-.89.88-.01 1.76l3.19 3.19q.88.88 1.76-.01l2.12-2.11q.88-.89 0-1.77M11 20.25h9.25");
}

:global(.yla1m8bvl) {
  d: path("m18.65 7.54l-3.19-3.19q-.88-.88-1.76 0L10.16 7.9q-.88.88 0 1.76l3.18 3.18q.88.88 1.76 0l3.55-3.54q.88-.88 0-1.76");
}

</style>
