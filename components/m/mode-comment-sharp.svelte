<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axd17qbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mode-comment-sharp" {...props}></Icon>
<style>
:global(.axd17qbjc) {
  fill: currentColor;
  d: path("M2 18V2h20v20l-4-4z");
}

</style>
