<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf4261bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:office-chair-home" {...props}></Icon>
<style>
:global(.wf4261bgy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 3l1 10.5h11.5m-6 0v4m-7 1.5l7-1.5l7 1.5m-14 2.75h.01m13.99 0h.01");
}

</style>
