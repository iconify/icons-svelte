<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="lxkkt6bcp"/><path class="ut88q0tta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:double-bend-sign" {...props}></Icon>
<style>
:global(.dh2jzoboc) {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

:global(.lxkkt6bcp) {
  d: path("M11.5 18.75c0-2.75-4-2.5-4-5.25s6.5-2 6.5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ut88q0tta) {
  d: path("M12.25 10.25L14 8.5l1.75 1.75");
}

</style>
