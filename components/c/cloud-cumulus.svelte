<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfvr0hucu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cloud-cumulus" {...props}></Icon>
<style>
:global(.hfvr0hucu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19.5a3.5 3.5 0 1 1 .99-6.86a5.5 5.5 0 1 1 9.02 0a3.5 3.5 0 1 1 .99 6.86Z");
}

</style>
