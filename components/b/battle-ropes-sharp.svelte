<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqxwc0bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:battle-ropes-sharp" {...props}></Icon>
<style>
:global(.sqxwc0bys) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5q2.25-3 4.5 0c2.25 3 3 2 4.5 0s3-2 4.5 0c1.25 1.6 3 3.6 4.75 4.5M2.75 16.5q2.25 3 4.5 0c2.25-3 3-2 4.5 0s3 2 4.5 0c1.25-1.6 3-3.6 4.75-4.5m.25-6.5v13");
}

</style>
