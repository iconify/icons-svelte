<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiu2y7byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:earbud-left-sharp" {...props}></Icon>
<style>
:global(.yiu2y7byd) {
  fill: currentColor;
  d: path("M6 22V12H3V4h9v18zm8-8V2h1q2.5 0 4.25 1.75T21 8t-1.75 4.25T15 14z");
}

</style>
