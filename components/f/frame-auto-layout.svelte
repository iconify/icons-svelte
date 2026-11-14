<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gexrfeb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:frame-auto-layout" {...props}></Icon>
<style>
:global(.gexrfeb0r) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25h14q2.75 0 2.75 2.75T19 7.75H5Q2.25 7.75 2.25 5T5 2.25m11 7H8q-2.75 0-2.75 2.75T8 14.75h8q2.75 0 2.75-2.75T16 9.25m-9.5 7h11q2.75 0 2.75 2.75t-2.75 2.75h-11q-2.75 0-2.75-2.75t2.75-2.75");
}

</style>
