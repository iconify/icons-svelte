<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okj8e-i-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expand-diagonal" {...props}></Icon>
<style>
:global(.okj8e-i-m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 7l10 10M14.5 5H19v4.5m-14 5V19h4.5");
}

</style>
