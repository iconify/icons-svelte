<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksjlc9wto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:equalizer-outline" {...props}></Icon>
<style>
:global(.ksjlc9wto) {
  fill: currentColor;
  d: path("M4 20v-8h4v8zm6 0V4h4v16zm6 0V9h4v11z");
}

</style>
