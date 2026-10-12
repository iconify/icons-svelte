<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbiovpbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boom-barrier-sharp" {...props}></Icon>
<style>
:global(.dbiovpbzy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5h4.5v14.75h-4.5zm4.5 2h14v3.75h-14zm4.25 0l-1.75 3.75M15.5 8.5l-1.75 3.75M19.5 8.5l-1.75 3.75");
}

</style>
