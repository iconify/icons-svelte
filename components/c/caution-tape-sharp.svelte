<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqgo0g9_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:caution-tape-sharp" {...props}></Icon>
<style>
:global(.xqgo0g9_x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.7 11.69l16.6-5.38l.95-.31v7l-.95.31l-16.6 5.38l-.95.31v-7zm1.55 5.5l2.25-5.73m1.75 4.43l2.25-5.73m1.75 4.43l2.25-5.73m1.75 4.44l2.25-5.73");
}

</style>
