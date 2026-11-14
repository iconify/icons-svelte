<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="u8rz5ub6c"/><path class="vc3-a0w7k"/><path class="g3wsk-qnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:file-sync" {...props}></Icon>
<style>
:global(.g3wsk-qnq) {
  d: path("m8 11l2 .25l-.75 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u8rz5ub6c) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M12 10.75a3.75 3.75 0 0 1 1.875 6.998");
}

:global(.vc3-a0w7k) {
  d: path("m16 18l-2-.25l.75-2M12 18.25a3.75 3.75 0 0 1-1.875-6.998");
}

:global(.w_a5jubhp) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
