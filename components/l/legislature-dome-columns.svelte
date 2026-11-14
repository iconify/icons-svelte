<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wydiidb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:legislature-dome-columns" {...props}></Icon>
<style>
:global(.wydiidb7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5c0-3 3-4.5 6.5-4.5s6.5 1.5 6.5 4.5Zm1 2.75v5.25m2.75-5.25v5.25M12 10.25v5.25m2.75-5.25v5.25m2.75-5.25v5.25M5 15.5h14m-15 3h16m-17 3h18");
}

</style>
