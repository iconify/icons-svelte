<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6qedzbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-large-outline" {...props}></Icon>
<style>
:global(.g6qedzbqk) {
  fill: currentColor;
  d: path("M2 20v-2h18V4h2v14q0 .825-.587 1.413T20 20zm4-4V6h12v10z");
}

</style>
