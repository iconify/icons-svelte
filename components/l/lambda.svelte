<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llnaj4buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lambda" {...props}></Icon>
<style>
:global(.llnaj4buv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 20l6.5-9.5M6.5 4c2 0 3 .5 3.5 2l5.5 12.5c.4.9 1 1.5 2.5 1.5");
}

</style>
