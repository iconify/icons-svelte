<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx-afxk5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caesura" {...props}></Icon>
<style>
:global(.fx-afxk5v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 20L11 4m2 16l5.5-16");
}

</style>
