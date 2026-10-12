<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irlnbhbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:recessed-light-sharp" {...props}></Icon>
<style>
:global(.irlnbhbva) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5m-14 0h9.5V9.5h-9.5v-2Zm4.75 6.5v3.5M7.75 12l-2 2.75M16.25 12l2 2.75");
}

</style>
