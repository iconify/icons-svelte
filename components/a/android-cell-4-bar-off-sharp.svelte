<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryoho3buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:android-cell-4-bar-off-sharp" {...props}></Icon>
<style>
:global(.ryoho3buz) {
  fill: currentColor;
  d: path("M20.4 20.925L16.5 18.2V20h-3v-3.9l-3-2.1v6h-3v-8.1L.75 7.15l1.425-2.025l19.65 13.75zm2.1-4.625l-3-2.1V4h3zM1.5 20v-8h3v8zm15-7.9l-3-2.1V7h3z");
}

</style>
