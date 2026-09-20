<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6u-_7r8k"/><path class="e948e9bse"/><path class="s__5d7blq"/><path class="wtehq4bsj"/><path class="bs41d9oln"/><path class="erdfj7vbx"/><path class="o_nzgwnjk"/><path class="vtgsa7bep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:conflict-duotone-regular" {...props}></Icon>
<style>
:global(.bs41d9oln) {
  d: path("m3 3 5 5");
}

:global(.e948e9bse) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 7v3.5H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.erdfj7vbx) {
  d: path("M10.5 7v3.5H7");
}

:global(.j6u-_7r8k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 3 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o_nzgwnjk) {
  d: path("m21 21 -5 -5");
}

:global(.s__5d7blq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 21 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vtgsa7bep) {
  d: path("M13.5 17v-3.5H17");
}

:global(.wtehq4bsj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 17v-3.5H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
