<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zggypbb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rosemary-sprig" {...props}></Icon>
<style>
:global(.zggypbb-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V3m0 15l-4-3m4 3l4-3m-4-2l-4-3m4 3l4-3m-4-2L9 5.5M12 8l3-2.5");
}

</style>
