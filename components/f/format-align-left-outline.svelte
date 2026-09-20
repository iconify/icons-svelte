<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhu6l4bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-align-left-outline" {...props}></Icon>
<style>
:global(.fhu6l4bta) {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h10v1zm0-3.75v-1h16v1zm0-3.75v-1h10v1zM4 5V4h16v1z");
}

</style>
