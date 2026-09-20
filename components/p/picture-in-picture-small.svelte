<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knv3vbckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-small" {...props}></Icon>
<style>
:global(.knv3vbckl) {
  fill: currentColor;
  d: path("M2 20v-2h18V4h2v14q0 .825-.587 1.413T20 20zm8-4v-6h8v6z");
}

</style>
