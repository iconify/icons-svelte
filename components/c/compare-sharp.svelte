<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha8lvbc5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:compare-sharp" {...props}></Icon>
<style>
:global(.ha8lvbc5u) {
  fill: currentColor;
  d: path("M10 23v-2H3V3h7V1h2v22zm-5-5h5v-6zm9 3v-9l5 6V5h-5V3h7v18z");
}

</style>
