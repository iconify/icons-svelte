<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4n15cbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bollard-sharp" {...props}></Icon>
<style>
:global(.i4n15cbvy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V10h4v11.25Zm7.25 0V7.5h4v13.75Zm7.25 0V10h4v11.25ZM2.75 15.5h4m3.25-2h4m3.25 2h4");
}

</style>
