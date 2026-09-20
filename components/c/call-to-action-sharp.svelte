<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjhur9baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:call-to-action-sharp" {...props}></Icon>
<style>
:global(.sjhur9baf) {
  fill: currentColor;
  d: path("M6 17h12v-3H6zm-4 3V4h20v16z");
}

</style>
