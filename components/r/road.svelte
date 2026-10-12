<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuf8ymu5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:road" {...props}></Icon>
<style>
:global(.wuf8ymu5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4q1 0 1.25.97l4.25 16.56q.25.97-.75.97H5.25q-1 0-.75-.97L8.75 3.72Q9 2.75 10 2.75m2 2.75v2m0 3.25v2.5m0 3.25V19");
}

</style>
