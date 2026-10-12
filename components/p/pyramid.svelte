<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diai4l4vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pyramid" {...props}></Icon>
<style>
:global(.diai4l4vw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.64 7.27l7.97 9.71q.64.77-.36.77H3.75q-1 0-.36-.77l7.97-9.71q.64-.77 1.28 0m-.34 3.23l.95 7.25M6.66 13h5.97");
}

</style>
