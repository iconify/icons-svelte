<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhksjsl_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expand-horizontal" {...props}></Icon>
<style>
:global(.dhksjsl_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16M8.5 8.5L5 12l3.5 3.5m7-7L19 12l-3.5 3.5");
}

</style>
