<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrjgwtdml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:filter-size" {...props}></Icon>
<style>
:global(.zrjgwtdml) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h18M3 12v6m18-6v6M7 15v2m4-2v2.5m4-2.5v2m4-2v2.5");
}

</style>
