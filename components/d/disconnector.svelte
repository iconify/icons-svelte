<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmgoucbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:disconnector" {...props}></Icon>
<style>
:global(.cmgoucbny) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5h5l8.5-9m.5 6v6m0-3h5m-14 0h.01");
}

</style>
