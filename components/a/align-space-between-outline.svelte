<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7gqzdbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-space-between-outline" {...props}></Icon>
<style>
:global(.a7gqzdbdf) {
  fill: currentColor;
  d: path("M7 7V4H2V2h20v2h-5v3zM2 22v-2h5v-3h10v3h5v2z");
}

</style>
