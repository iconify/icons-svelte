<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zov8t3bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minus-linear" {...props}></Icon>
<style>
:global(.zov8t3bqn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 12L4 12");
}

</style>
