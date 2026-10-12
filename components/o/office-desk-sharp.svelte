<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ttyib5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:office-desk-sharp" {...props}></Icon>
<style>
:global(.b4ttyib5z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h18.5V10H2.75zM5 10v11.25m7.5-9h8v9h-8zM15.25 15h2.5m-2.5 3.5h2.5");
}

</style>
