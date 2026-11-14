<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiyr1mcya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:centrifugal" {...props}></Icon>
<style>
:global(.yiyr1mcya) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-6V2.5m-2 2l2-2l2 2M12 18v3.5m-2-2l2 2l2-2M6 12H2.5m2-2l-2 2l2 2M18 12h3.5m-2-2l2 2l-2 2");
}

</style>
