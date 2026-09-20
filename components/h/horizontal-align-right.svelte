<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3q5nphy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:horizontal-align-right" {...props}></Icon>
<style>
:global(.zc3q5nphy) {
  fill: currentColor;
  d: path("M19 19V5h1v14zm-7-2.692l-.708-.708l3.1-3.1H4v-1h10.392l-3.1-3.1l.708-.708L16.308 12z");
}

</style>
