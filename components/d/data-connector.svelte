<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tijqe008i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-connector" {...props}></Icon>
<style>
:global(.tijqe008i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9h5a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m0-5.5V9m5-5.5V9M12 15v5.5");
}

</style>
