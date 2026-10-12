<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bimwbug2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coat-rack-sharp" {...props}></Icon>
<style>
:global(.bimwbug2h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v15.75m0-.5l-4.25 3m4.25-3l4.25 3M12 7L7.75 4.5M12 7l4.25-2.5m-4.25 7L8.25 9.25M12 11.5l3.75-2.25");
}

</style>
