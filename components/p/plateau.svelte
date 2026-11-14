<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnrrs83sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plateau" {...props}></Icon>
<style>
:global(.qnrrs83sy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 19l2.5-6l2-1l1.25-5.5H16l1.25 5l1.75 1l1.5 6.5m-18 0h19");
}

</style>
