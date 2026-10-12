<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn28gkqbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bookmark-sharp" {...props}></Icon>
<style>
:global(.rn28gkqbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25v-2.5h12.5v19.058l-1.6-1.108L12 17.25L7.35 20.7l-1.6 1.108V19.85Zm3.5 2h5.5");
}

</style>
