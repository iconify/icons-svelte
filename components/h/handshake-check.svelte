<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5uxbc2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:handshake-check" {...props}></Icon>
<style>
:global(.zg5uxbc2l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h5l3-2H14l3.5 2.5h4m-19 6H6l4.5 3H13l4-3h4.5M5 6v6.5m14-6v6m-10.5-4l3 3M12 7l3 3m-.25 8l2 2L21 15.75");
}

</style>
