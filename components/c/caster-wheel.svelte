<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovq01mbys"/><path class="kxai-hb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caster-wheel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kxai-hb4u) {
  d: path("M7.25 15.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m4.75 0h.01");
}

:global(.ovq01mbys) {
  d: path("M7 3.25h10m-5 0v4.5m-7.5 8v-8h15v8");
}

</style>
