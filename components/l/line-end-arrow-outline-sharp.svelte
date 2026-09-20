<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhs9ccc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-arrow-outline-sharp" {...props}></Icon>
<style>
:global(.hhs9ccc9u) {
  fill: currentColor;
  d: path("M11 19v-6H2v-2h9V5l11 7zm2-3.65L18.275 12L13 8.65zM13 12");
}

</style>
