<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny8-jsb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:backslash" {...props}></Icon>
<style>
:global(.ny8-jsb5u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 3.5l10 17");
}

</style>
