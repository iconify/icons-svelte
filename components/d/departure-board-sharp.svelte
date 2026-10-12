<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekmtzjb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:departure-board-sharp" {...props}></Icon>
<style>
:global(.ekmtzjb2o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5V16.5H2.75zM6 7h3m-3 3.25h3M6 13.5h3M11.75 7H18m-6.25 3.25H18m-6.25 3.25h4M7 16.5v4.75m10-4.75v4.75");
}

</style>
