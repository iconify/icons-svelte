<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx2kf4bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-draft-fill" {...props}></Icon>
<style>
:global(.wx2kf4bcr) {
  fill: currentColor;
  d: path("M6 8.829v6.342a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2 0M19.01 5a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2ZM16 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
