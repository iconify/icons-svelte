<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h967h1b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:grid-view-sharp" {...props}></Icon>
<style>
:global(.h967h1b_v) {
  fill: currentColor;
  d: path("M4 11V4h7v7zm0 9v-7h7v7zm9-9V4h7v7zm0 9v-7h7v7z");
}

</style>
