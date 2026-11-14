<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgjlv1o0e"/><path class="ve0vvhtpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cnc-machine" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ve0vvhtpj) {
  d: path("M9.75 3h4.5A1.75 1.75 0 0 1 16 4.75v2a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 6.75v-2A1.75 1.75 0 0 1 9.75 3M12 8.5v7m-2.75 0h5.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 14.75 21h-5.5a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75");
}

:global(.xgjlv1o0e) {
  d: path("M4 21V3h16v18M2.5 21h19");
}

</style>
