<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx_klccox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:glue-sharp" {...props}></Icon>
<style>
:global(.xx_klccox) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10.25h11.5v11H6.25zm3.5 0l.75-3.5l1.5-4l1.5 4l.75 3.5Zm-.5 5h5.5");
}

</style>
