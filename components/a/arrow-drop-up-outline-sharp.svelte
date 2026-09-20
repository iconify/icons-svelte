<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bczq3c8be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-drop-up-outline-sharp" {...props}></Icon>
<style>
:global(.bczq3c8be) {
  fill: currentColor;
  d: path("M8.192 13.5L12 9.692l3.808 3.808z");
}

</style>
