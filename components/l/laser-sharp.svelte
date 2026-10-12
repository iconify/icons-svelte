<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjg9bcbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:laser-sharp" {...props}></Icon>
<style>
:global(.pjg9bcbwf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8.25h9.5v2.25h2.25v3h-2.25v2.25H2.75v-7.5zm1 3.75h3.5m9.25 0h2.75m-2.5-4.25l2-1.25m-2 9.75l2 1.25");
}

</style>
