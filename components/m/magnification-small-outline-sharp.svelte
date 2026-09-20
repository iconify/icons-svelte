<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkjb066wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:magnification-small-outline-sharp" {...props}></Icon>
<style>
:global(.wkjb066wf) {
  fill: currentColor;
  d: path("M5.5 10.5h3v-3h-3zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
