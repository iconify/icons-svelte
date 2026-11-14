<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7i8zmiam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:incident-report" {...props}></Icon>
<style>
:global(.j7i8zmiam) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 18.5l2.75-15h1.5l2.75 15Zm-2 2h11M6 9h4m-5 5h6m5.5-11h4v13.5l-2 4l-2-4Zm0 3h4m-4 10.5h4");
}

</style>
