<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n18gh5b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:overview-key-sharp" {...props}></Icon>
<style>
:global(.n18gh5b6l) {
  fill: currentColor;
  d: path("M1 19V5h14v14zm16 0V5h2v14zm4 0V5h2v14z");
}

</style>
