<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngvt5_q2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fax-sharp" {...props}></Icon>
<style>
:global(.ngvt5_q2x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h2.5v13.5h-2.5zm5 1.5h13.5v12H7.75zm3 0v-6.5H17L19.25 5v4.25M11 13.5h6.75M11 17.25h6.75");
}

</style>
