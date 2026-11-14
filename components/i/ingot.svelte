<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xewcj8bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ingot" {...props}></Icon>
<style>
:global(.xewcj8bav) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18h19L19 11l-2.5-5h-9L5 11ZM5 11h14");
}

</style>
