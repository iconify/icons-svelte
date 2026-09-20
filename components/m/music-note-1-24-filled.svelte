<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8rhe5lge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:music-note-1-24-filled" {...props}></Icon>
<style>
:global(.e8rhe5lge) {
  fill: currentColor;
  d: path("M11.513 2.048a.75.75 0 0 0-1.013.702v12.127a4 4 0 1 0 1.476 3.56a.8.8 0 0 0 .024-.187V8.832l6.987 2.62A.75.75 0 0 0 20 10.75V7.483a3.25 3.25 0 0 0-2.109-3.044z");
}

</style>
