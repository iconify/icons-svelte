<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s39qlqbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:play-pause" {...props}></Icon>
<style>
:global(.s39qlqbvb) {
  fill: currentColor;
  d: path("M5 16.2V7.8l6 4.2zm8-.2V8h2v8zm4 0V8h2v8z");
}

</style>
