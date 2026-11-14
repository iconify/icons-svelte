<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzpxu8upg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caret-left" {...props}></Icon>
<style>
:global(.yzpxu8upg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.684 10.901l3.295-3.06A1.5 1.5 0 0 1 14.5 8.94v6.12a1.5 1.5 0 0 1-2.521 1.099l-3.295-3.06a1.5 1.5 0 0 1 0-2.198");
}

</style>
