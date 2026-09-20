<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai2q2obhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:expand-more" {...props}></Icon>
<style>
:global(.ai2q2obhe) {
  fill: currentColor;
  d: path("m12 15.375l-6-6l1.4-1.4l4.6 4.6l4.6-4.6l1.4 1.4z");
}

</style>
