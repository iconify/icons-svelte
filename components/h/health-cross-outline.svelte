<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukqf22deb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:health-cross-outline" {...props}></Icon>
<style>
:global(.ukqf22deb) {
  fill: currentColor;
  d: path("M8 21v-5H3V8h5V3h8v5h5v8h-5v5zm2-2h4v-5h5v-4h-5V5h-4v5H5v4h5zm2-7");
}

</style>
