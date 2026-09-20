<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snwv1qmfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-h4-outline" {...props}></Icon>
<style>
:global(.snwv1qmfj) {
  fill: currentColor;
  d: path("M3 17V7h2v4h4V7h2v10H9v-4H5v4zm15 0v-3h-5V7h2v5h3V7h2v5h2v2h-2v3z");
}

</style>
