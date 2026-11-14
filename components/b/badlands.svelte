<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie8y40bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:badlands" {...props}></Icon>
<style>
:global(.ie8y40bcu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 19.5l3-7H8L9.5 7h7l1.5 5.5h1l2.5 7ZM11.75 7v5.5M14.5 7v7.5");
}

</style>
