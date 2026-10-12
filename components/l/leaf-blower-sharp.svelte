<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ick91xd2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:leaf-blower-sharp" {...props}></Icon>
<style>
:global(.ick91xd2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8h7.5v9h-7.5zm2 0V4.25H9.5V8m1.49 2.15l4.77.95l.74.15v3l-.74.09l-4.77.57l-.74.09v-5zm8.01 1.1l2.25-.75M19 14.25l2.25.75");
}

</style>
