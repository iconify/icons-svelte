<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3pvhobox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:plumbing-pipe-sharp" {...props}></Icon>
<style>
:global(.h3pvhobox) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10H2.75v4H8m8-4h5.25v4H16m-6 2.75v4.5h4v-4.5M8 7.5h8v9.25H8z");
}

</style>
