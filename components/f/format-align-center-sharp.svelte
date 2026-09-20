<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ospkjfbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-align-center-sharp" {...props}></Icon>
<style>
:global(.ospkjfbda) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm4-4v-2h10v2zm-4-4v-2h18v2zm4-4V7h10v2zM3 5V3h18v2z");
}

</style>
