<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt594-ldn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-right-outline" {...props}></Icon>
<style>
:global(.wt594-ldn) {
  fill: currentColor;
  d: path("M10.5 15.808V8.192L14.308 12z");
}

</style>
