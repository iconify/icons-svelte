<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0c9fnbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:local-bar" {...props}></Icon>
<style>
:global(.k0c9fnbbv) {
  fill: currentColor;
  d: path("M6 21v-2h5v-5L3 5V3h18v2l-8 9v5h5v2zM7.45 7h9.1l1.8-2H5.65z");
}

</style>
