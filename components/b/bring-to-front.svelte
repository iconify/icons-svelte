<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zvvr-_bsq"/><path class="bmborbbpd"/><path class="k6yjb7b_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bring-to-front" {...props}></Icon>
<style>
:global(.bmborbbpd) {
  d: path("M12.25 16.25h-3a1.5 1.5 0 0 1-1.5-1.5v-5.5a1.5 1.5 0 0 1 1.5-1.5h5.5a1.5 1.5 0 0 1 1.5 1.5v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6yjb7b_t) {
  fill: currentColor;
  d: path("M14.875 12.25h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25a2.625 2.625 0 0 1-2.625-2.625v-3.25a2.625 2.625 0 0 1 2.625-2.625");
}

:global(.zvvr-_bsq) {
  d: path("M7.75 11.75h-3a1.5 1.5 0 0 1-1.5-1.5v-5.5a1.5 1.5 0 0 1 1.5-1.5h5.5a1.5 1.5 0 0 1 1.5 1.5v3");
}

</style>
