<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6wuk5vxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-vertical-bottom-outline-sharp" {...props}></Icon>
<style>
:global(.e6wuk5vxx) {
  fill: currentColor;
  d: path("M3 20.5v-1h18v1zm4.692-3.577V3.481h2.039v13.442zm6.577 0V9.481h2.039v7.442z");
}

</style>
