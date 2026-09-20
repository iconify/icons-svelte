<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdnt74bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:5g-outline-sharp" {...props}></Icon>
<style>
:global(.pdnt74bqf) {
  fill: currentColor;
  d: path("M3.5 16.5v-1h5v-3h-5v-5h6v1h-5v3h5v5zm17-5v5h-8v-9h8v1h-7v7h6v-3H17v-1z");
}

</style>
