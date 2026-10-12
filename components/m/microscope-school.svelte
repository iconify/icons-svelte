<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jb_o0_bfd"/><path class="b75m7v3tb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:microscope-school" {...props}></Icon>
<style>
:global(.b75m7v3tb) {
  d: path("m12.6 12.75l.8 1.5m.1-7.35c3 .6 5.25 3.1 5.25 6.35c0 2.6-1.4 4.6-3.5 5.6v2.4m-10.5 0h14.5M6.75 16.5h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jb_o0_bfd) {
  d: path("m10.44 4.16l3.44 5.55q.53.85-.32 1.38l-2.12 1.32q-.85.53-1.38-.32L6.62 6.54q-.53-.85.32-1.38l2.12-1.32q.85-.53 1.38.32");
}

</style>
