<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyk3mhabr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parchment" {...props}></Icon>
<style>
:global(.hyk3mhabr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4q3.5-1.5 7 0t7 0v16q-3.5 1.5-7 0t-7 0Zm3.5 5h7m-7 4.5h5");
}

</style>
