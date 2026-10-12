<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ine6s8bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bone" {...props}></Icon>
<style>
:global(.ine6s8bno) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 14.16l6.44-6.44a2.5 2.5 0 1 1 3.85-1.73a2.5 2.5 0 1 1-1.73 3.85l-6.44 6.44a2.5 2.5 0 1 1-3.85 1.73a2.5 2.5 0 1 1 1.73-3.85");
}

</style>
