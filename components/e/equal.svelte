<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6pouu4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:equal" {...props}></Icon>
<style>
:global(.qb6pouu4l) {
  fill: currentColor;
  d: path("M4 17v-3h16v3zm0-7V7h16v3z");
}

</style>
