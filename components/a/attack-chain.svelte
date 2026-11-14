<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xhrzxacyk"/><path class="m4ga1lxem"/><path class="iw5cr1mws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:attack-chain" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iw5cr1mws) {
  d: path("m13.995 6.823l2.828-2.828a2.25 2.25 0 0 1 3.182 0a2.25 2.25 0 0 1 0 3.182l-2.828 2.828a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182");
}

:global(.m4ga1lxem) {
  d: path("m8.995 11.823l2.828-2.828a2.25 2.25 0 0 1 3.182 0a2.25 2.25 0 0 1 0 3.182l-2.828 2.828a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182");
}

:global(.xhrzxacyk) {
  d: path("m3.995 16.823l2.828-2.828a2.25 2.25 0 0 1 3.182 0a2.25 2.25 0 0 1 0 3.182l-2.828 2.828a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182");
}

</style>
