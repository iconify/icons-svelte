<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t683rry-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fast-rewind" {...props}></Icon>
<style>
:global(.t683rry-g) {
  fill: currentColor;
  d: path("M19.904 16.616L12.98 12l6.923-4.615zm-8.885 0L4.096 12l6.923-4.615z");
}

</style>
