<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfeig5b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:lab-profile-sharp" {...props}></Icon>
<style>
:global(.yfeig5b2b) {
  fill: currentColor;
  d: path("M8.5 11.5h7v-1h-7zm0-4h7v-1h-7zM19 20.07l-4.275-5.57H5V3h14zM5 21v-5.5h9.25l4.216 5.5z");
}

</style>
