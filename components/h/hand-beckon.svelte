<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfjwnhbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hand-beckon" {...props}></Icon>
<style>
:global(.jfjwnhbxe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5v-2.75l-3.75-4a1.75 1.75 0 0 1 2.5-2.5L9 13.5v-7a2.5 2.5 0 0 1 5 0V9m-1 3h3.5a2.5 2.5 0 0 1 2.5 2.5v2a5 5 0 0 1-3 4.5v.5");
}

</style>
