<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foh-fybmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:context-overflow-sharp" {...props}></Icon>
<style>
:global(.foh-fybmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.25h16.5v13H3.75zm3.5 9.5h9.5M12 14.25V2.75M8.75 6L12 2.75L15.25 6");
}

</style>
