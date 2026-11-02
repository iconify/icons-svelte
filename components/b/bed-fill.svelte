<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdpr_pbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-fill" {...props}></Icon>
<style>
:global(.hdpr_pbpa) {
  fill: currentColor;
  d: path("M4 8h2v9H4v2a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 9V8h11a3 3 0 0 1 3 3v8a1 1 0 0 1-2 0v-2Z");
}

</style>
