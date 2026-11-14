<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg-wuov-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aircraft-carrier" {...props}></Icon>
<style>
:global(.hg-wuov-y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19l-2 5.5H5Zm12 0V8.5h4V13m-2-4.5v-3");
}

</style>
