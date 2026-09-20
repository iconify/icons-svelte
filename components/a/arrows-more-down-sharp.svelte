<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1qw01bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrows-more-down-sharp" {...props}></Icon>
<style>
:global(.s1qw01bzr) {
  fill: currentColor;
  d: path("M6 20V10h1v9h9v1zm4-3.98v-10h1v9h9v1z");
}

</style>
